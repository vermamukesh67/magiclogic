# magiclogic
This project just have magic apis in swift that can be used for extra ordinary logic.


Get the nearest round number multiplied of 10

 func roundToTens(_ x : Double) -> Int {
     return 10 * Int((x / 10.0).rounded())
 }
