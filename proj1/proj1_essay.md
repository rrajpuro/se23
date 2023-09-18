# Project 1, Essay <a name="head"></a>
Project 1, A project with an aim to train us to assess and reuse other people's code. And work with code written by students from this subject and make them work.

We tried to pen down our journey in this essay.
So this is how we started;
- We went through all the repos that were assigned to us,
- We eyeballed what could be appropriate to not only run but extend, (This part was a very crucial part as it):
  - could define our plan of action for the future project
  - Could give us, the team, an idea of what to plan (learn new technologies for extension or just understand the existing code)
- Mutual agreement in what to do next.

Now, getting a project running and being able to extend it is a very different thing. So, finding one such project that was apt for both tasks was very important for us.
However, over the course of project1, we will accept that we made some [mistakes](#mistakes) that, if avoided, could have made our lives very easy!

## Part1: <a name="part1"></a>
We had two options, to start off with grading/start off with running a project. Upon team voting we decided to grade first. Reasons behind choosing it is that:
- It would give us a better understanding of the repo, the project and prerequisites (one required things like external AWS DB, one needed Telegram API)
- And lastly, it would give us a hint about how the project documentation is and how to maintain the code (it would be a good starting point in maintaining the code if at least the documentation is in its place).

So, we started grading and made CSV files with our results. Once done, we then got a basic idea of what project to run and what to just keep aside as a 2nd,3rd or 4th option.

## Part2: <a name="part2"></a>
Now, going straight to the part2, running a project.
- We started with the project [(WolfTrack3.0)](https://github.com/nehajaideep/WolfTrack3.0). This project was made to help us with job application and tracking. We tried to run it but soon found out that this application was dependent on “AWS Relational Database Service-RDS” as a primary DB by the location. But, for running it/contributing to the project, they requested us to mail to “wolftrackse@gmail.com” to get the AWS IAM user account details to connect to AWS RDS. This was a big drawback. So we had to stop all efforts to try running this application.

- Moving on to [(C.E.L.T Sentiment Analyzer)](https://github.com/mrpudlo/SE_Project1/), upon checking the tech stack, we found out that it was more into Jupyter Notebooks and some machine learning and speech/audio recognition. Now, using python was not a problem, but we discussed that no one on our team had experience with using the above mentioned technologies. And we thought that it would be better to have this project as a 2nd option because it would take the team a lot less time to work on existing technologies and learn a few rather than learning a lot of new technologies. So, we kept this one aside.

- Then we went to [(ItemStockTracker)](https://github.com/shahrk/ItemStockTracker/): The application looked like it would be a good fit for running and extension, but upon proper thinking, we found out that given its name and the nature of product, there was not a lot to extend apart from enhancing existing features, like adding more retailers is just adding to existing list of retailers, adding coupon codes/discount alerts is an added feature but it goes beyond the scope of the project, especially its name and to find one, we either will have to use APIs or scrape for coupons, which is the same. So, we decided to move on to the next project.

- Testing [(Units Converter Extension)](https://github.com/NCSU-S/units_converter_extension/), this is where we saw easy and successful run and implementation. We did see the application working on the Chrome browser as an extension which aided in unit conversion upon selection. It did work fine. We selected it to work on. But then we faced a big problem, how will we be able to extend it? Is there any major scope of extension where we could do considerable work and extend the project? We thought about it a lot, but then came to terms that it would be very difficult to do so as this application covered a wide arrays of units to convert (we had to dig into the source code to get that)

- So, finally, we tested the [(MyDollarBot-BOTGo)](https://github.com/prithvish-doshi-17/MyDollarBot-BOTGo), the Telegram bot to record, track and display expenses. This being a Telegram bot, it was cross-platform and would work with any device. This seemed promising as it was dependent on Telegram, which is a standard application with well-defined APIs and documentation. We tried to run it without going through the documentation properly, but it wasted a lot of our time. We then properly read through the doc and then ran it and it did run! Now, we had to think about extending it. We were able to come up with some initial plans like changing the format of its responses, adding alerts, reminders, giving better numbers and graphs etc.

After a lot of meetings and failures, we finalized to use MyDollarBot-BOTGo to be the project to be used to create the video and use it for our project2.

## Mistakes: <a name="mistakes"></a>
Now, we know that we were not at all perfect and made a lot of small and big mistakes throughout the process of project1. We then thought about it and then decided to not repeat them in the future projects. Here are some of the mistakes we made:
- We did not host regular meetings, we met very sparsely and at random times, it hurt our efficiency to work
- We made a mistake of not ranking the projects after grading them. Yes, after testing each one of them, we found out that our grading was very close to our results. If we would have ranked the projects, we could have just avoided running some of the projects based on the documentation and their dependencies.
- We didn’t use the divide and conquer strategy. We just stuck to pure teamwork and no-division of work. This was slightly harmful to our working speed. Each has its own advantages and disadvantages. So, in the future, instead of completely following a teamwork/divide and conquer model, we would want to follow a hybrid model, a combination of teamwork, collaboration and divide and conquer. That would be with some tradeoffs, but we are ready to face them.
