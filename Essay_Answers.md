 //  Part 2: Essay Questions


 //1. What is the difference between forEach and for...of? When would you use each?
      
   //forEach method we can use it with arrays to execute function for every element It dosent support break or continue

     //for...of loop that iterate through array values and It allow to use break and continue

     // I use forEach for simple loops on arrays
     // I use for...of when I need break or continue



 //2. What is hoisting and what is the Temporal Dead Zone (TDZ)? Explain with examples

     // Hoisting move variable declarations to top before execute code
     // var can be access before declaration but value will be undefined
     // let and const cannot be used before declaration

     // TDZ the time before let or const is declaration
     //If we use variable before declaration JS throw error
 
     // console.log(x);
      //  var x = 5;
      // Output: undefined
 
 
     // console.log(y);
     // let y = 6;
      // Output: ReferenceError


 //3. What are the main differences between == and ===?

      // == compare values 
      // === compare value and data type

      // Example
      // 5 == "5"  // true        same value
      // 5 === "5" // false       same value but different data type num , srting


 //4. Explain how try-catch works and why it is important in async operations

     // try contain code may throw an error
     // catch handle that error
     //It prevent program from stopping
    // It is important in async operations because API request or network request may fail
      
      // Example
       // try {
        // console.log(x);
        // } catch (err) {  
         //   console.log("Something went wrong");  
          //   }

     // x notdefined // catch handle error and program not stop



 //5. What’s the difference between type conversion and coercion? Provide examples of each

      // type conversion convert data type manually 
      // Coercion convert data type automatically

      // Example for type conversion
      // Number("5")   // 5

     // Example for coercion
     // "5" + 4       // "54"

      // "5" - 4  // 1

     // "5" * 4   // 20

     // "20" / 5   // 4

     // (+) JS treat value as string
     //  (-), (*),(/) JS convert string to number first




