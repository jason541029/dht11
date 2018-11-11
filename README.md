# dht11
var parameter = {
  url: 'https://docs.google.com/spreadsheets/d/1-AE26BWLp8Vjz_bVITRFVRJpvRTx-qOgXwNuwFyhch8/edit#gid=0',
  name: '工作表1',
  startRow: 1,
  startColumn: 1
};
$.get('https://script.google.com/macros/s/AKfycbx11W86suAwzJqKCghefUqfGC3I9I_677rxF8eZXOtfW8fsKDM/exec', parameter, function(data) {
  console.log(data);
});
