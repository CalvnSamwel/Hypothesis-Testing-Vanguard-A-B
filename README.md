# Hypothesis-Testing-Vanguard-A-B

# **Project Overview** 🚀  
This study aimed to determine whether a redesigned user interface (UI) with modern, intuitive elements and in-context prompts (e.g., cues, messages, hints) would enhance user experience and boost the completion rates of a multi-step online process, concluding with a final confirmation page. The experiment used **A/B testing**:  
- **Control Group**: Clients interacting with the traditional UI.  
- **Test Group**: Clients engaging with the redesigned, modern UI.  

The goal was to assess if the new interface provided a smoother and more user-friendly experience, as indicated by higher completion rates.  

---

# **Questions** ❓  
The study focused on three core research questions:  
1. **Completion Rate**: Does the redesigned UI improve completion rates compared to the traditional design?  
2. **Time Spent**: How much time do users spend on each step of the process in both the Test and Control groups?  
3. **Error Rates**: What are the error rates observed for each group during various steps?  

---

# **Dataset** 📊  
Three critical datasets were utilized for the analysis:  
1. **Client Profiles**: Contains demographic information such as age, gender, and account details [Link](https://github.com/data-bootcamp-v4/lessons/blob/main/5_6_eda_inf_stats_tableau/project/files_for_project/df_final_demo.txt).  
2. **Digital Footprints**: Logs client interactions online, provided in two parts that required merging [Part 1](https://github.com/data-bootcamp-v4/lessons/blob/main/5_6_eda_inf_stats_tableau/project/files_for_project/df_final_web_data_pt_1.txt) and [Part 2](https://github.com/data-bootcamp-v4/lessons/blob/main/5_6_eda_inf_stats_tableau/project/files_for_project/df_final_web_data_pt_2.txt).  
3. **Experiment Roster**: Lists participants involved in the experiment [Link](https://github.com/data-bootcamp-v4/lessons/blob/main/5_6_eda_inf_stats_tableau/project/files_for_project/df_final_experiment_clients.txt).  

---

# **Main Dataset Issues** ⚠️  
1. **Data Imbalance**: Uneven sample sizes in the Control and Test groups required careful statistical adjustments for valid comparisons.  
2. **Complex User Behavior**: Analyzing user progress through multiple steps introduced challenges, especially for users who revisited steps or spent varying amounts of time on each one.  
3. **Error Rate Variations**: Identifying errors across different steps was critical but challenging, as small discrepancies could impact results significantly.  

---

# **Conclusions** ✅  
The redesigned UI demonstrated clear improvements for younger users, with higher completion rates and reduced time spent per step. However, older users faced challenges, showing higher error rates and spending more time navigating the process. These findings suggest the new interface is promising but requires optimization to address the specific needs of older demographics.  

---

# **Next Steps** ⏭️  
1. **Redesign Problematic Steps**: Focus on steps with higher error rates to improve usability for older users.  
2. **Support Features for Older/First-Time Users**: Introduce tooltips, tutorials, or in-context guidance tailored to these user groups.  
3. **Demographic-Specific Usability Testing**: Conduct focused sessions with older users to identify and resolve pain points effectively.  
4. **Personalized UI Options**: Offer adaptive interfaces—streamlined for younger users and guided for older users or beginners.  
5. **Continuous Metric Monitoring**: Track completion rates, time spent, and error rates post-implementation to evaluate ongoing effectiveness across all age groups.  

By addressing these steps, the redesigned UI can evolve into a universally inclusive and effective solution for diverse user demographics! 😊  
