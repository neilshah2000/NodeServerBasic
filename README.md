# NodeServerBasic
one file to create a basic node server



var express = require('express');
var app = express();
app.use('/', express.static(__dirname)); // ← adjust
app.listen(3000, function () {
    console.log('listening');
});
