# Jimmy_GonzalezPortfolio
A portfolio for my code
this is a bit of code that i have made in swift

// made by Jimmy Gonzalez
//this code asks the user questions and puts them in a sentence. 

var sName = AskQuestion(sQuestion:"what is your name?");


print("Hi \(sName), you are a \(sGender), and your hair is \(sHair).")



func AskQuestion(sQuestion:String) -> String
{
  print(sQuestion)
  return String(readLine()!)
}
