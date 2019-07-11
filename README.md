第一题
var user = {};
user.name = "John";
user.surname = "Mike";
user.name = "Peter";
delete user.name;

第二题
var fruit = {
    apple: 20,
    pear: 20,
    peach: 10
};

function fruit_number(fruit) {
    fruitNumber = fruit.apple + fruit.pear + fruit.peach;
    return fruitNumber;
}

var fruitNumber;
fruit_number(fruit);
document.write(fruitNumber);
