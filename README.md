# Predicting-Status-of-an-Interview
## Machine Learning Project ( Supervised )

You are a data scientist of a big MNC who usually hires more than 10k candidates every year.
To complete the task they conduct more than 1 lakhs of interviews every year.

Interview-Intel is the modern way to approach hiring by harmonizing all aspects of the interview process into a beautiful symphony.
An interview intelligence tool records, transcribes, and analyzes candidate conversations. 
It helps the hiring managers, recruiters, and HR Business Partners (HRBPs) to gain deeper visibility into the interview process, 
create smooth feedback loops between the panellists, and improve the overall recruitment process.

You need to predict the status of the interviews so that recruiters can check the sanity of the interview and find if the interview was biased


### Detailed description:
	
- Interview Id : Id for the interview
- Candidate Id : Id for the candidate
- Interviewer Id : Id for the interviewer
- Profile : Profile type
- S.L.R.C (Speak to Listen Ratio Candidate): It is the ratio of speaking time to the listening time of the Candidate.
- S.L.R.I (Speak to Listen Ratio Interviewer): It is the ratio of speaking time to the listening time of the Interviewer.
- A.T.T Avg Turn Time (Interactivity Time): It is the average amount of time in which single interaction happens between the Interviewer and the Candidate.
- L.M.I (Longest Monologue Interviewer): It is the longest amount of time that the interviewer spoke continuously.
- L.M.C (Longest Monologue Candidate): It is the longest amount of time that the candidate spoke continuously.
- S.R (SILENCE RATIO):It is the percentage of time when no one had spoken
- L.J.T.C (Late Joining Time Candidate): It is the amount of time a candidate joined late for the interview call.
- L.J.T.I (Late Joining Time Interviewer): It is the amount of time the interviewer joined late for the interview call.
- N.I.C(Noise Index Candidate): Percentage of Background Noise present on the candidate side.
- N.I.I(Noise Index Interviewer): Percentage of Background Noise present on the interviewer’s side.
- S.P.I - Speaking Pace interviewer: Average Number of words spoken per minute.
- S.P.C - Speaking Pace Candidate: Average Number of words spoken per minute.
- L.A.I - Live Absence interviewer: It is the percentage of time the interviewer was not present in the video call.
- L.A.C - Live Absence candidate: It is the percentage of time the candidate was not present in the video call.
- Q.A - Question asked during the interview
- P.E.I - Perceived Emotion Interviewer: It is the perceived emotion of Interviewer which can be either Positive or Negative
- P.E.C - Perceived Emotion Candidate: It is the perceived emotion of candidate which can be either Positive or Negative
- Compliance ratio - Does the interviewer follow the structure that has been guided by the company. It is the ratio of questions assigned to the number of questions which were actually asked.
- Interview Duration : For how much time interview happened
- Interview Intro :Does interviewer give the self-introduction to the candidate or not
- Candidate Intro :Does candidate give the self-introduction to the interviewer or not
- Opp to ask : Does the interviewer give a chance to the candidate to ask questions at the end.
- Status : Status of the candidate.
