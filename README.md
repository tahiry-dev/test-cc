# Code Refactoring

> An example of code refactoring for better performance


## Built With

- Javascript

## Getting Started

**To get this project set up on your local machine, follow these simple steps:**

**Step 1**<br>
Navigate through the local folder where you want to clone the repository and run<br>
`git clone https://github.com/tahiry-dev/test-cc.git`. It will clone the repo to your local folder.<br>
**Step 2**<br>
get inside the local folder where you cloned the repository, and open the file called refactoring.js with your favorite code editor

## Complexity of the refactored code
    
   ### Time complexity: 
   - The following functions don't depend on any input; hence, they have a constant time complexity of O(1): 
     addRice, cookRice, steam, keepWarm, removeRice, delaySync.

   - The simulateRiceCooker function contains a while loop that will run indefinitely until the user chooses to exit (input 6). 
     If we assume that the user will eventually choose option 6 to exit the program,
     we can analyze the time complexity based on the maximum number of iterations the loop would run before the user chooses option 6. 
     Let's denote this maximum number of iterations as N. The while loop runs N times, where N is the maximum number of iterations before the user chooses option 6. 
     Therefore, the time complexity of the simulateRiceCooker function, considering the user will eventually choose option 6, is linear: O(N).

   - Since the other parts are just constants, the time complexity of the program is O(N), linear as well.
   
  ### Space complexity:
   - All the functions inside the program do not use any data structures or allocate memory that depends on the size of the input. 
     Instead, they perform a fixed number of operations with a constant amount of memory usage. Therefore, the space complexity is constant: O(1).

## Complexity of the Original Code

You can find the original code [here](https://github.com/hei-school/cc-d4-rice-cooker-ci-NyAndoMayah/blob/feat/js/js/main.js)

  ### Time complexity

  - addRice, cookRice, steam, keepWarm, removeRice, delaySync functions:
    These functions have constant time complexity O(1) because their execution time does not depend on the size of any input.
  - simulateRiceCooker function:
    Inside the function, there is a while loop that runs until the user exits. The memory used within each iteration of the loop is constant.
    The variable input and choice are updated based on user input, and they use a constant amount of memory for their operations.
    There are no dynamic data structures or memory allocations that scale with the input size.
    Therefore, the space complexity of the simulateRiceCooker function is constant O(1).
Hence, similar to the refactored code, the time complexity of that program is 0(N)

 ### Space complexity

   - addRice, cookRice, steam, keepWarm, removeRice, delaySync functions:
     These functions individually have constant space complexity O(1) because they use a fixed amount of memory regardless of the input.
   - simulateRiceCooker function:
     Inside the function, there is a while loop that runs until the user exits. The memory used within each iteration of the loop is constant.
     The variable input and choice are updated based on user input, and they use a constant amount of memory for their operations.
     There are no dynamic data structures or memory allocations that scale with the input size.
     Therefore, the space complexity of the simulateRiceCooker function is constant O(1).
Hence, the space complexity of the program is 0(1)

## Authors

👤 **RANDRIAMIARINTSOA Tahiry**

- Github: [tahiry_dev](https://github.com/tahiry-dev)
- Twitter: [@tahiry](https://twitter.com/Tahiry94825074)
- Linkedin: [Randriamiarintsoa](https://www.linkedin.com/in/tahiry-randriamiarintsoa/)

## 🤝 Contributing

My favorite contributions are those that help me improve the project, whether with a contribution, an issue, or a feature request!

## Show your support

If you've read this far....give us a ⭐️!

## 📝 License

This project is licensed under the MIT License.


