#NodeStatusMonitor

Credit to:
what this embeds: [statusdashboard](https://github.com/obazoud/statusdashboard)
and for the heartbeat monitor: http://github.com/chamerling 
and of course Douglas Crockford and other js gods
    
## Notes on the heartbeat plugin

The application is deployed on Heroku at http://YOURAPP.herokuapp.com and periodically pings defined services. In order to keep it alive, the application also pings itself with the statusdashboard heartbeat plugin. When deploying for the first time, the HEARTBEAT_URL must be set like

    heroku config:add HEARTBEAT_URL=http://YOURAPP.herokuapp.com

## Alternatives

https://github.com/evantahler/nodeChecker


## License

(The MIT License)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS
IN THE SOFTWARE.