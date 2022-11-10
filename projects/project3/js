var main = function() {
    var volume;
  
  //The PLAY button
 $('#play').click(function(){
    $('#message').text("Playing track");
    $('#player').trigger("play");
 });

 //The PAUSE button
 $('#pause').click(function(){
    $('#message').text("Track paused");
    $('#player').trigger("pause");
 });

 //The MUTE button
 $('#mute').click(function(){
    $('#message').text("Track muted");
    $('player').prop("muted");
    $("#player").prop('muted', true);
 });

 //The UNMUTE button
  $('#unMute').click(function(){
    $('#message').text("Track not muted");
    $('player').prop("muted");
    $("#player").prop('muted', false);
 });

 //The STOP button 
  $('#stop').click(function(){
    $('#message').text("Track stopped");
    $('#player').trigger("pause");
    $('player').prop("currentTime");
    $("#player").prop('currentTime', 0);
 });

 //The VOLUME UP button
  $('#volUp').click(function(){
    $('#player').trigger('volume')
    VolumeUp= $('#player').prop('volume')
    $("#player").prop('volume', VolumeUp+0.1);
 });

 //The VOLUME DOWN button
 $('#volDown').click(function(){
    $('#player').trigger('volume')
    VolumeDown= $('#player').prop('volume')
    $("#player").prop('volume', VolumeDown-0.1);
 });

}

$(document).ready(main);
