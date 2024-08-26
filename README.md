  Variables named , , and  are declared for you in the editor below. You must use the  operator to perform the following sequence of operations:

1 - Convert  to an integer (Number type), then sum it with  and print the result on a new line using console.log.
2 - Convert  to a floating-point number (Number type), then sum it with  and print the result on a new line using console.log.
3 - Print the concatenation of  and  on a new line using console.log. Note that  must be printed first.

function performOperation(secondInteger, secondDecimal, secondString) {
    const firstInteger = 4;
    const firstDecimal = 4.0;
    const firstString = 'HackerRank ';
    console.log(firstInteger + Number(secondInteger));
    console.log(firstDecimal + Number(secondDecimal));
    console.log((firstString || '').concat(secondString));
}
