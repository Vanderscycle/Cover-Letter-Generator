
# Cover Letter Generator

On applying for jobs, it is difficult to keep track of cover letters and the amount of job application can sometimes make writing a cover letter error prone such as wrong company name, typos and format problem.
Cover Letter Generator solves the problems above. It gets rid of simple mistakes and helps you automate writing cover letters. Of course you can still add customized cover letters and everything would be saved for future reference. 

## Getting Started

Clone the project.

Run:
```
pip install requirements.txt
```

## How to use

run
```
make
```

The program will prompt a list of questions and after some simple answers it will generate a cover letter.
Here is an example:

## Structure of the cover letter

The information of the company as well as personal information stored in info.json

Here is my core structure of the cover letter

* Contact Information: name, address, phone, email, website, github, etc.
* Open Paragraph: Greeting paragraph stating the intention of your cover letter
* First coop: experience from your first coop
* Second coop: experience from your second coop
* Extra curricular activities: Choose up to 4 from a pools of software activities that I pursue.
* Final pararaph: closing paragraph, thank the company and state the availability time(optional)


## Built With

* [python-docx](https://python-docx.readthedocs.io/en/latest/) - python doc library
* [abiword](https://www.abisource.com/) - Convert word to pdf

## Future Development (TODOs)

* Make the structure more flexible
* Add tags to archived paragraphs

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
