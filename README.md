# Jimmy_GonzalezPortfolio
A portfolio for my code
This is a code that i have created in swift. 

//Made by Jimmy Gonzalez Jr. 

var sName = AskQuestion(sQuestion:"what is your name?");


print("Hi \(sName), you are a \(sGender), and your hair is \(sHair).")



func AskQuestion(sQuestion:String) -> String
{
  print(sQuestion)
  return String(readLine()!)
}
