# ContextCRBench

You can access the dataset of task 1 (Quality Estimation) at this link:

https://drive.google.com/file/d/1Iy0zaT3Fta7TeU6QsNBxK7iuzeGYMrvJ/view?usp=drive_link

You can access the dataset of task 2 (Defect Localization) at this link:

https://drive.google.com/file/d/10_gM9eXinPm8WwH4S2eDazlxQ1vRbh1M/view?usp=drive_link

You can access the dataset of task 3 (Review Comment Generation) at this link:

https://drive.google.com/file/d/10_gM9eXinPm8WwH4S2eDazlxQ1vRbh1M/view?usp=drive_link

Each of the above datasets contains 1080 entries, and ensures a balanced distribution in terms of time and programming language under the merge scenario (specifically for Task 1).

You can access the output of three tasks (Quality Estimation, Defect Localization, Review Comment Generation) at this link:

https://drive.google.com/file/d/1g2kYy-yYtLl5mJAYUTJMiCWqvm1fsGW6/view?usp=drive_link.

We have also added all the prompts to it.

The structure of our data entry is:

{

  "id": int
  
  "full_name": str
  
  "lang": str
  
  "issue_number": int
  
  "issue_title": str
  
  "issue_body": str
  
  "issue_comment":     Array [str]
  
  "pr_number": int
  
  "pr_title": str
  
  "pr_body": str
  
  "pr_comment":     Array [str]
  
  "merged": bool
  
  "created_at": str
  
  "commit_id": str
  
  "original_commit_id": str
  
  "path": str
  
  "start_line": int
  
  "original_start_line": int
  
  "start_side": int
  
  "line": int
  
  "original_line": int
  
  "side": str
  
  "original_position": int
  
  "position": int
  
  "subject_type": str
  
  "review_comment":     Array [str]
  
  "diff_hunk": str
  
  "diff_hunk_head": str
  
  "diff_hunk_content": str
  
  "diff_hunk_content_with_line_number": str
  
  "diff_hunk_original_start_line": int
  
  "diff_hunk_original_end_line": int
  
  "diff_hunk_start_line": int
  
  "diff_hunk_end_line": int
  
  "file_path_before": str
  
  "file_path_after": str
  
  "comment_lines":     Array [str]
  
  "content_before": str
  
  "content_after": str
  
  "snippet_before": str
  
  "snippet_start_line_before": int
  
  "snippet_end_line_before": int
  
  "snippet_after": str
  
  "snippet_start_line_after": int
  
  "snippet_end_line_after": int
  
  "all_line_number":     Array [str]

}
