Split method in Javascript

We have split method in js that we apply to strings it takes two argument both are optional. First one is based on what we need to split the string. second one is how many arrays we want.

let str = 'sai harshitha';
str.split(' '); // it splits like ['sai', 'harshitha'];
str.split(' ', 1) // it splits like ['sai'] //1 is we want only one element in an array,
str.split('') //it splits by every character and puts in an array
str.split(' ').join('-') // output is sai-harshitha

let message = 'The day is blue. Grass is green! do you know the color of grass';
message.split(); // it outputs like ['Yes, You can do it']
we can do array destructing

const [firstName, lastName] = str.split(' '); // firstName is sai lastName is harshitha

