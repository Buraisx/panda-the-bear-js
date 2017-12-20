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
var listItem = document.createElement('li');
var leftSpan = document.createElement('span');
var lastUpdated = document.createTextNode('Page last updated on');
var date = document.createElement('span')
leftSpan.appendChild(lastUpdated);
listItem.appendChild(leftSpan);
listItem.appendChild(date);

var bioInfo = document.querySelector('.bio-info')
listItem.classList = 'bio-info-item'
date.classList = 'bio-info-value'
lastUpdated.classList = 'bio-info-title'

bioInfo.insertAdjacentElement('beforeend', listItem)

var t = new Date()
t.toLocaleString('en-us')
date.innerText = t
