# Pavel Sizemov
<img style="width: 300px; heigh: 300px;"
src="https://sun1-85.userapi.com/s/v1/ig2/IGUUWOUXG86BAZYbp4Q-RFnuqQ_OmlbC9jdBkKnuBPk05Iu-lVqnGnUcoboFz6wKNdtTOmpLRflSy7LTvjkfvfi2.jpg?size=400x0&quality=96&crop=0,270,1620,1620&ava=1">
## Contact Information
+ Discord:  paulgrossman
+ Telegram: https://t.me/PaulGrossman
+ E-mail: sizemovpavel@gmail.com

## About me
I am currently working in the field of marketing and at the same time I am getting an education in the field of programming. I started learning programming a couple of years ago, but due to the demands of my job, it was difficult for me to allocate enough time for effective learning. Despite these difficulties, my desire for technology and web development has only intensified.

Now I am determined to complete my education and start a career as a junior interface developer. I would like to apply my knowledge and skills in a professional environment where I can contribute to dynamic projects and continue to learn from experienced colleagues.

## Skills
+ Git, Github
+ HTML
+ CSS
+ JavaScript
+ Jest

## Code Example

**Task:** Implement and export by default a function that accepts a list of emails as input, and returns the number of emails located on each free domain. The list of free domains is stored in the freeEmailDomains constant

```
const freeEmailDomains = [
  'gmail.com',
  'yandex.ru',
  'hotmail.com',
];

const getFreeDomainsCount = (emails) => {
  const mapDomain = emails.map((email) => email.split('@'));
  const listDomain = mapDomain.map((domain) => domain[1]);
  const filterDomain = listDomain.filter((list) => freeEmailDomains.includes(list));
  const cb = (acc, item) => {
    acc[item] = (acc[item] || 0) + 1;
    return acc;
  };
  const result = filterDomain.reduce(cb, {});
  return result;
};
export default getFreeDomainsCount;
```
## Work experience
Currently, there is no experience in commercial development. In the course of training, I completed 2 projects:

1. **Brain-games** is a series of 5 console mini-games that can entertain you and become a warm-up for your brain.<br>
Link to github - [Brain-games](https://github.com/SizemovPavel/frontend-project-lvl1)

2. **Difference generator**. The utility finds and displays differences in configuration files.Works with files .json, .xml. Three output formats are available: "stylish" by default, "regular" and "json".<br>Link to github - [Difference generator](https://github.com/SizemovPavel/frontend-project-46 )

## Education
+ Hexlet Courses
+ Rolling Scopes

## Languages
+ English - A2
+ Russian - Native