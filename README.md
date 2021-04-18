# Python Fundamentals (also called "Core Python" and "Introduction to Python")

## Knowledge Transfer: The point of this is to help instructors who have never taught this before understand the class and the audience, etc.

### Audience
* The intended audience is that same as it would for an "Introduction to Java", "Introduction to Go", etc. That is, the intended audience is folks who know how to code in at least one other language and want to "laterally" apply those skills to Python.
* However, this course–because it's taught in Python–is often mistaken for a "learn to code" course.
* As such students in this course often have either no programming background, or a background in Bash, PowerShell, or SQL. I think we can agree those are not bona fide programming languages, and therefore, if that is their only background, they really need a course like "Introduction to Programming" (probably should be renamed "Learn to Code").
* But as an instructor who is tasked with teaching this course, you can't really die on that hill. You can suggest that folks w/o the appropriate background consider the "Introduction to Programming" course, but that doesn't mean they have to listen.
* Bottom line is that it's likely you'll have a mix of backgrounds–some folks will be developers who know Java or JavaScript, etc., and others will not have a programming background or will be DevOps-type folks with a bit of scripting under their belts.

### Teaching the Course
* Any course where there are students at differing levels will be difficult. The goal is to find the sweet spot. In the unlikely (but possible) event that all students are expecting an Intro to Programming course, then you should teach that. Ensure you have access to those materials.
* More likely, you'll have two groups, and you'll want to be mindful of that. Some exercises have "extra" parts that can be assigned to the more advanced students and the beginners can skip it. You can also assign additional work for the more advanced students, or sometimes pair them up with a less advanced counterpart (easier for an ILT than a VILT).
* If there are more advanced students then apologize to the ones with a lesser background and move at a faster pace. Let the beginners know you will help them at breaks and after class and also remind them of Intro to Programming.
* If there are more beginners, then do the opposite. Your goal is to satisfy as many of the students as you can, not necessarily follow the outline.
* Someone is bound to be unhappy and may well complain about it. That's OK, it's how we get these disparities fixed on the client side. Once they see the "wrong" people are signing up, they'll be more open to discussions about how to fix.

### Logistics
* While it is not required, I would suggest when starting the course and getting the students set up with Jupyter notebooks, show them you are creating a _new_ notebook for yourself called "Workbook". Use it to demonstrate concepts and answer student questions. That way you won't make changes directly to the materials, and the students will have an additional takeaway. (The students can–and should–work directly in their notebooks, but as the instructor you don't really want to do that.) I tell the students that I will give them the Workbook after the class is over, but if they prefer, I provide it in its current state at the end of each day. I typically have a Google Drive folder in which I disseminate the materials, so it's easy to put the Workbook there and overwrite the previous version at the end of each day. If you're really ambitious, you can make a pass over the Workbook after class is over, adding notes and comments to further clarify what you did. It's not required, of course, and you might consider combining cells for clarity and adding a few notes while you're demonstrating to keep the content "tight."
* A great teaching site which is referenced in the materials is www.pythontutor.com. I recommend having that open and using it to demonstrate concepts that are difficult.
* Another browser tab I like to have open during the class is the built-in functions from Python docs (just Google "Python built-in functions to get the latest"). That way as we discuss functions such as __`int`__(), __`len`__(), __`type`__(), etc. I can help them understand the difference between built-in functions and methods (e.g., list methods) that we run across later. I make clear that the docs are opaque, and aimed at folks who know Python well, and, as such, should be skimmed (or "zoomed out") as needed. Sometimes the info about a particular function is not at all useful to beginners so don't try to push it on them.
* I often show the __`id`__() function to demonstrate the concept of "Everything is an object" in Python. All they have to understand is that every "thing" (variables, functions, modules, etc.) lives in memory and can be discovered with that function. It's also interesting to note that there are many functions one never uses in real code–__`id`__(), __`help`__(), __`dir`__(), etc.
### Python 2 vs. 3
* This course originally contained a section about Python 2 vs. 3, and at various points during the course, we'd discuss 2 vs. 3 differences. That section has been removed and I recommend only speaking about 2 vs. 3 if students indicate it's a concern. Some teams still have Python 2 codebases, for example.

### Suggested Pacing
* The course is divided into three notebooks roughly representing each day's materials. Depending on the students, you may well not get through the entire notebook by the end of the day. This is normal, so just let the students know that it's OK to be a bit "behind" as there is a lot of material. I typically tell students that courses contain 10-20% additional material that often isn't covered because it's difficult to gauge the exact amount of material and of course, audiences are different. You don't wan't to shut down questions because you are trying to cover all the material. Better to invite questions and be sure foundational material is well understood. 
* You will **very likely not get through all of the Day 3 materials**. It's extremely rare that I've ever covered the final topic–OO programming in Python. This is fine–that material is replicated and covered more in depth in the Intermediate course, so unless you have a class full of solid developers, I can't imagine getting there.
