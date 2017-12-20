1.  var profileImage = document.querySelector('.profile-image') <br />

2.  var cloud = document.querySelector('#left-image > img')<br />

3.  var pandaHeader = document.querySelector('h1')<br />
    pandaHeader.innerText = 'William'

4.  var employmentHeader = document.querySelector('#employment>.info-title')<br />
employmentHeader.innerText = 'Unemployment'

5.  var body = document.body<br />
    body.style.color = 'yellow'


6.  var highlights = document.querySelectorAll('.highlight')<br />
highlights.forEach(function(highlight){<br />
highlight.style.backgroundColor = 'blue'<br />
})

7.  var h1Fonts = document.querySelectorAll('h1')<br />
  h1Fonts.forEach(function(header){<br />
header.style.fontFamily = 'monospace'<br />
})


8.  var roundIcons = document.querySelectorAll('.action-icon-bg')<br />

roundIcons.forEach(function(icon){<br />
icon.style.backgroundColor = 'red'<br />
})


9. var nameField = document.querySelector('#name')<br />
nameField.placeholder = 'identify yourself'


10. var messageField = document.querySelector('#message')<br />
messageField.placeholder = 'state your business'


11. nameField.value = 'your nemesis'<br />


12. var emailField = document.querySelector('#email')<br />
emailField.value = 'koalathebear@gmail.com'

13. var submit = document.querySelector('#submit')<br />
submit.value = 'En garde!'

14. submit.disabled = true<br />

15. var bioInfo = document.querySelector('.bio-info')<br />
    document.querySelector('aside').removeChild(bioInfo)
