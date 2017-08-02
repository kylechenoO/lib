######################################################################
Lock.py Usage:
# lock initial
self.lockObj = Lock(
    self.pname,
    self.pid,
    self.config.LOCK_DIR,
    self.config.LOCK_FILE,
    self.logger)

# ... ...

# lock release
try:
    self.lockObj.lock_release(self.config.LOCK_FILE)
except Exception as e:
    pass

######################################################################
Crontab.py Usage:
while True:

    # crontab initial
    self.crontabObj = Crontab(
        self.config.CRONTAB_CFG_FILE,
        self.logger,
        self.config.MAX_THREADS,
        self.config.THREAD_TIMEOUT,
        self.config.SUBPROC_LIMITS,
        self.config.MAX_RETRY,
        self.config.THREAD_DELAY)
        self.crontabObj.run()
    time.sleep(self.config.SERVICE_INTERVAL)

######################################################################
Config.py Usage:
# You can read some values from Config.py file for some Configuration File
config = Config(WorkPath)
print(config.workpath)
