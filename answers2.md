1.
$('.bar-default:nth-child(3n)').remove()<br />

2.
var newPika = document.querySelector('#right-image > img').cloneNode()<br />
var portfolioCointainer = document.querySelector('.portfolio-container')<br />
portfolioContainer.insertAdjacentElement('afterend',newPika)

3.
for(var i = 0; i<10;i++){ <br />
portfolioContainer.appendChild(newPika.cloneNode())<br />
}


4.
var listItem = document.createElement('li');<br />
var leftSpan = document.createElement('span');<br />
var lastUpdated = document.createTextNode('Page last updated on');<br />
var date = document.createElement('span')<br />
leftSpan.appendChild(lastUpdated);<br />
listItem.appendChild(leftSpan);<br />
listItem.appendChild(date);<br />

var bioInfo = document.querySelector('.bio-info')<br />
listItem.classList = 'bio-info-item'<br />
date.classList = 'bio-info-value'<br />
lastUpdated.classList = 'bio-info-title'<br />

bioInfo.insertAdjacentElement('beforeend', listItem)<br />

var t = new Date()<br />
t.toLocaleString('en-us')<br />
date.innerText = t
