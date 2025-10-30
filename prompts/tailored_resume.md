# 1 - Parse Job Description
## 1.1 - Job Duties
```
Read through the following job description and make a bulleted list of the job duties. Recount the job duties as verbatim as possible.

INSERT_JOB_DESCRIPTION
``` 

## 1.2 Requirements
```
Read through the job description again and make a bulleted list of the job's requirements. Recount the job requirements as verbatim as possible.
```

## 1.3 Skills
```
Read through the job description again and make a bulleted list of skills organized in the following categories: hard skills, soft skills, tools/technology. Recount the skills as verbatim as possible. Hard skills are skills that involve tactical execution of tasks while soft skills are skills that are general, intangible, qualitative, and/or baseline professional skills (communication, organization, attention to detail, etc.). 
```

# 2 - Work History
## 2.1 - Draft Bullet Points
```
I want the bullet points in my resume to be as explicit as possible to 1:1 match with the criteria, making it as easy/clear as possible to sway the hiring manager. Ask me questions to walk me through each piece of work history, then form the bullet points based on my answers.

Here's the conversational flow:
1. Ask for job title and company
2. Ask which criteria or requirements ("jd_point") fit for this piece of work history
3. Ask how I performed insert_jd_point_here
4. Respond with a bullet point
5. If I say "Next Job", go to Step 1
6. If there are no more jd_points from Step 2 for this piece of work history, go to Step 1
7. Otherwise, go to next jd_point
```

## 2.2 - Map Directly to JD
```
Now that we've completely fleshed out our bullet points, we need to make them more organized and concise, while also giving a full picture of what I did.

I'm going to give you one or more bullet points, and then I'm going to give you the criteria listed on the job description.

I need you to take the bullet point(s) and write it such that it directly maps to the jd_point.

The flow is:
1. Receive jd_point from user
2. Receive bullet point(s)
3. Output result that maps to jd_point
4. Repeat 2 and 3 until user says "next jd_point
5. Go to 1

To make things as clear as possible, use similar language as the jd_point in your result. Do no worry about the length of your output, but do NOT just rehash or repeat the bullet points you're given.

This is the first jd_point: JD_POINT_HERE

This is the first set of bullet points: BULLET_POINTS_HERE
```

## 2.3 - Trimming
```
Now we need to make these more concise. I will give you a jd_point. Then, I will give you a set of one or more bullet points. You give me a concise version of each bullet point, keeping the pertinent information and removing extraneous or overly deep details. Make sure you still convey the skill and duties mentioned in the jd_point, and provide enough specificity for the reader to understand how the skill was applied. Make sure to maintain the language of the jd_point as well.

This is the first jd_point: INSERT_JD_POINT

This is the first set of bullet points: INSERT_BULLET_POINTS_HERE 
```

## 2.4 Quantification
```
Now we want to quantify bullet points where we can. The quantifications should go down the following order, from highest to lowest priority:

A) Quantifications related to the mapped job duty
B) Quantifications related to the overall target role
C) Quantifications related to the target job function
D) Quantifications that directly map to the work history's bullet point
E) Quantifications that reflect achievement at work history role

For each work history, provide a thorough, comprehensive list of quantifications and denote which level each one would be at. Go one work history at a time.
```

```
Now integrate quantified achievements (quantifications) directly into the concise bullet points for each role.

Here are the quantifications for each role:
INSERT_QUANTIFICATIONS_HERE
```

## 2.5 Ordering Bullet Points
```
Now we're going to organize the bullet points. Here is the workflow order:
1. User provides list of bullet points for one work history
2. For each work history, organized the bullet points into the following categories:
    A) Hard skill with quantified metric related to target role's job duties
    B) Hard skill with quantified metric related to target role's job function
    C) Soft skill with quantified metric related to target role's job duties
    D) Soft skill with quantified metric related to target role's job function
    E) Hard skill with quantified metric related to work history
    F) Soft skill with quantified metric related to work history
    G) Hard skill with no quantified metric
    H) Soft skill with no quantified metric

NO bullet point WITHOUT a number should be above a bullet point WITH a number.

3. List the bullet points according to their categories in the following order: Category A, Category B, Category C, Category D, Category E, Category F, Category G, Category H

4. Ask user for next set of bullet points

As a reminder, here is the list of hard and soft skills:

SKILLS_LIST_HERE
```

## 2.6 Role Summaries
```
Here are the lists of hard and soft skills you created earlier:

SKILLS_LIST_HERE

Using these lists and everything you know about my work history, create concise, clear summaries of the soft skills used in each position. Make sure key phrases, keywords, etc. map closely to the wording of the original soft skill's bullet point.

For each position summarize the employer, role, and soft skills used in a concise paragraph.

Do NOT use first person. DO use present tense.

Treat each paragraph as a summary to be used on the resume. The structure of each paragraph should be similar to the following:

EMPLOYER_NAME help CLIENTS_AND_CUSTOMERS by GOODS_OR_SERVICE. As part of their duties, the JOB_TITLE SOFT_SKILLS_SUMMARY
```

# 3 - Skills Section
## 3.1 - Getting the List
```
Now let's work on the skills section. As a reminder, here's the job description:

INSERT_JOB_DESCRIPTION_HERE

Perform the following workflow:
1. Read through the job description
2. Compile a list of skills in the form of keywords and key phrases
3. Organize those skills into categories
4. Refine your list into a polished Skills Section ("refined list"), grouped under categories, for my resume.
```

## 3.2 - Tailoring Skills to Resume
```
Now tailor each category of this refined list to my resume while keeping the wording as close to the original job description as possible. Keep the format to keywords and key phrases. Do NOT get into details or attributes specific to subject matters.

Return your result as a bulleted list with each bullet point formatted as follows:
SKILL_CATEGORY_TITLE: comma-separated list of keywords and key phrases
```

# 4 - Professional Summary
```
Now we want to write a professional summary. Here are the key points that should be mentioned:
    1. Unique characteristic to set them apart from typical applicants for target job
    2. Title similar to target job title that properly reflects the experience in the resume
    3. Number of years of GENERAL_JOB_FUNCTION experience
    4. Culture/ethos-alignment framed as reason for seeking target job
    5. Reason for change, especially if previous employers do not seem immediately aligned with ethos of target employer

Here is a rough draft for this role and resume:
INSERT_ROUGH_DRAFT_HERE

The summary should be similar to the following format:
UNIQUE_CHARACTERISTIC_ADJECTIVE_FROM_STEP_1 SIMILAR_TITLE_FROM_STEP_2 with NUMBER years of GENERAL_JOB_FUNCTION experience. STATEMENT(S)_THAT_CAPTURE_STEP_4_AND_STEP_5 
```