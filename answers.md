1.  var profileImage = document.querySelector('.profile-image')

2.  var leftImage = document.querySelector('#left-image')
    var cloud = leftImage.querySelector('img')

3.  var pandaHeader = document.querySelector('h1')
    pandaHeader.innerText = 'William'

4.  var employmentHeader = document.querySelector('#employment>.info-title')
employmentHeader.innerText = 'Unemployment'

5.  var body = document.body
    body.style.color = 'yellow'


6.  var highlights = document.querySelectorAll('.highlight')
highlights.forEach(function(highlight){
highlight.style.backgroundColor = 'blue'
})

7.  var h1Fonts = document.querySelectorAll('h1')
  h1Fonts.forEach(function(header){
header.style.fontFamily = 'monospace'
})


8.  var roundIcons = document.querySelectorAll('.action-icon-bg')

roundIcons.forEach(function(icon){
icon.style.backgroundColor = 'red'
})


9. var nameField = document.querySelector('#name')
nameField.placeholder = 'identify yourself'


10. var messageField = document.querySelector('#message')
messageField.placeholder = 'state your business'


11. nameField.value = 'your nemesis'


12. var emailField = document.querySelector('#email')
emailField.value = 'koalathebear@gmail.com'

13. var submit = document.querySelector('#submit')
submit.value = 'En garde!'

14. submit.disabled = true

15. var bioInfo = document.querySelector('.bio-info')
    document.querySelector('aside').removeChild(bioInfo)
