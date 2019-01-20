# dot-match-exploring
figuring out how to use . match

writing some code to explore how .match works.

heres some stuff pulled from codewars that i found after failing a challenge. REF:

function getCount(str) {
  return (str.match(/[aeiou]/ig)||[]).length;
}

var vowels = str.match(/[aeiou]/ig);
if (vowels === null) {
  return 0;
} else {
  return vowels.length;
}
