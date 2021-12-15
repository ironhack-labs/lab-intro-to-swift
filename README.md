
![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Lab | Intro to Swift

## Learning Outcomes

After completing this lab, you will be able to:

- Create variable properties
- Use string interpolation on String properties
- Use if / else statements to conditionally change a view
- Use arithmetic operators to maintain a view's size's ratio

## Requirements

- Fork this repository.
<!-- - Add your instructor and the class graders to your repository and ensure that your repository is private. Public repositories will receive a zero on the assignment.
  - If you are unsure who your class graders are, ask your instructor or refer to the day 1 slide deck. -->
- Upload the code for all of the following prompts to your repository.

## Submission

- Upon completion, run the following commands:

  ```shell
  git add .
  git commit -m "done"
  git push origin main
  ```

- Create a Pull Request

When you make pull request in pair-programming: `student1,student2-nameOfTheExercise` <br>
When you make pull request in individual-programming: `student-nameOfTheExercise`

<br>

## Introduction

In today's lab, we will see how we can use variables, multiplications & divisions to improve our designs and make them adaptive with ratios.
Why adaptive? Because different devices have different screen sizes, and we want our apps to look just as great on all of them!
As a bonus, you might get to figure out a nifty trick many developers often use to figure out whether a number is odd, or even.

### Starter code

In the repo you have forked, we provide you with a starter code. This code contains a starter Swift Playground you are going to build from. We will be starting where we left off in the last lesson's last activity.

<!-- Sandra: The below is not needed anymore - to be removed after validated with an SME -->
<!-- Adjust the starter code to the needs of the students and the lessons that they covered so far.

```swift
//: A UIKit based Playground for presenting user interface
  
import UIKit
import PlaygroundSupport

class MyViewController : UIViewController {
    override func loadView() {
        let view = UIView()
        view.backgroundColor = .white

        let label = UILabel()
        label.frame = CGRect(x: 150, y: 200, width: 200, height: 20)
        label.text = "Hello World!"
        label.textColor = .black
        
        view.addSubview(label)
        self.view = view
        
        var name = "Anna"
        label.text = "My name is \(name)"
        
        var darkMode = true
        if darkMode {
            view.backgroundColor = .black
            label.textColor = .yellow
        } else {
            view.backgroundColor = .white
            label.textColor = .blue
        }
    }
}

// Present the view controller in the Live View window
PlaygroundPage.current.liveView = MyViewController()
``` -->

### Iterations

#### Iteration 1

In this iteration you are expected to:
- declare two new var variables: a `height` variable and a `width` variable.
- replace the height and width for the label.frame with these variables.

<br>

#### Iteration 2

In this iteration you are expected to:
- make your view's label's height one half (1/2) of its width using a multiplication operator.

<br>

#### Iteration 3

In this iteration you are expected to:
- make your view's label's height one half (1/2) of its width using a division operator.

<br>

#### Iteration 4 (Bonus)

In this iteration you are expected to:
- randomize the view's width, as a value between 0 and 400. Hint: search on Google how to get a random Int value in Swift.
- randomize the darkMode variable's value.

<br>

#### Iteration 5 (Bonus)

In this iteration you are expected to:
- use an arithmetic operator to find if the view's width is even. Hint: you can use the modulo operator.
- assign the result of this operation to the darkMode variable

<br>

#### Iteration 6 (Bonus)

In this iteration you are expected to:
- replace your label's text (`"My name is \(name)"`) with `"short string"` if your label's width is less than 70
- replace your label's text (`"My name is \(name)"`) with `"a slightly longer string"` if your label's width is greater than or equal to 70, and less than 150
- replace your label's text (`"My name is \(name)"`) with `"a very, extremely, supercalifragilisticaly longer string"` if your label's width is greater than or equal to 150

<br>

Happy coding! :heart:
