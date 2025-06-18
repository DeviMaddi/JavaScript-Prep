# JavaScript-Prep

1. Diff bw Java & JS
Java is a compiled, object-oriented programming language used mainly for backend development, Android apps, and enterprise applications. It runs on the Java Virtual Machine (JVM) and is known for its strong typing and scalability.

On the other hand, JavaScript is a lightweight, interpreted scripting language mainly used for web development to make websites interactive. It runs in the browser and can also run on the server using environments like Node.js.

2. DataTypes in JS:
    Primitive: Number, String, Boolean, Undefined, Null, BigInt
    Non Primitive: Objects, functions, Arrays

3. Newest Version of JS: ES2023 -- ECMA2023

4. Cohersion - JS converts one datatype to another data type automatically
     Implicit Cohersion -- Automatically converts -- "5" + 1 = "51"
     Explicit Cohersion -- We have to Manually convert -- Number("5") -- 5

    "5" + 1 = "51"
    "5" - 1 = 4
     3 + 2 + "7" = "57"


5. Falsy - null, undefined, NaN, 0, -0, false,  "" -- only these 7 fixed, rest of all are true values
   Truthy - {}, [], "hi", 1,

6. Undeclared & Undefined:
   Undefined Variable
   A variable that is declared but has no value assigned.
   let x;
   console.log(x); // ✅ Output: undefined

    Undeclared Variable
    A variable that has never been declared at all.
    Accessing it directly will throw a ReferenceError.
    console.log(y); // ❌ ReferenceError: y is not defined

7. Global Variables:
   are the variables that define outside of functions. These variables have a global scope, so they can be used by any function without passing them to the function as parameters.
   *It is difficult to debug and test the code that relies on global variables.

8.NULL - NO VALUE/OBJECT - EMPTY VALUE/OBJECT 

9. how to delete a prop from an objecct ?
   use delete prop
   delete object.property;
   delete object["property"];

  let user = {
  name: "Devi",
  age: 23,
  city: "Hyderabad"
};

delete user.city;


10. Diff bw undefined and null:
    undefined means a variable has been declared but not assigned any value — it's the default value assigned by JavaScript.
    null, on the other hand, is an intentional assignment to indicate no value or empty value.

11. 

