<!doctype html><html><head><meta charset="UTF-8"/><title>WG后台管理系统</title><link rel="icon" href="favicon.ico"/><meta name="viewport" content="width=device-width,initial-scale=1,user-scalable=no"/><meta http-equiv="X-UA-Compatible" content="ie=edge"/><script defer="defer" src="/static/runtime~main.9bd2183cfabc30bbc886.js"></script><script defer="defer" src="/static/main.c550dbc19d67e03c9127.js"></script></head><body data-version="1746581800352"><div id="app"></div></body><script defer="defer">window.addEventListener('load', function() {
      if ('serviceWorker' in navigator) {
        navigator.serviceWorker.getRegistrations().then(function(regs) {
          for (var key in regs) {
            regs[key].unregister()
          }
          navigator.serviceWorker
            .register('/service-worker-1746581800352.js')
            [
              // .then(function () {
              //   console.log('serviceworker register success')
              // })
              'catch'
            ](function(err) {
              console.error('serviceworker register fail')
            })
        })
      }
    })</script></html>
