--- # Finding optimized methods #----

Please note this had to be added as a zip as it had over 100 files, somehow?! 

Screenshots of the output and information on how to get the project to debug properly are attached, may be useful consider the 117mb project attached.

This projects main method contains 2 simple lines of C# code, calling another class containing 3 methods and loops that perform the same function. The benchmark tests all of these methods extensively and gives a final report displaying the median, mean and best times. One can use this for any similar codes to find the most optimized version, helping them develop optimized, fast software.

Simply running the project will bring up an option panel, once the user clicks 'Continue debugging' (as displayed in attached screenshots), they will see hundreads of lines being read on the console. This 
debugging process run the set methods hundreads of times. This feature has many usecases in software testing before implementation and will prove useful in my development journey.

To use this benchmark code you will need the BenchmarkDotNet Nuget package avaliable on Visual Studios.

Then, as seen in the screenshots attached you will need to set output form to debug and set the top options, next to the 'run' icon to release and any cpu. This allows the project to debug in a specific way and show the debugging output, being the optimization.

Options one needs to change for this to work:
![requirements2 0](https://user-images.githubusercontent.com/101861214/178943203-ce99a65f-6dea-47a8-aaeb-3707db2b06bd.png)

The pre-run option panel prompt:
![continuedebugging](https://user-images.githubusercontent.com/101861214/178943070-26ffb09f-6f6b-4f07-893f-f61a454ce6eb.png)

How it looks while running the tests:
![Processes](https://user-images.githubusercontent.com/101861214/178943350-460754f7-1e63-421f-898a-9c07d9213bf1.png)

The final output and consensus:
![benchmarkoutput](https://user-images.githubusercontent.com/101861214/178943389-84a96c80-216e-469f-ac79-9d4e9fb67879.png)
