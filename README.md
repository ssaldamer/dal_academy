# DAL applicant simulation

I wanted to know how I might compare with the people likely to apply to DAL Academy. I could not use real applicants, so I built a synthetic pool, simulated how it would answer the DAL self-assessment, and compared the result with my own answers.

## Files

- `DAL_inference_scored.xlsx`: curriculum scores for 10 degree programmes against the 45 competencies, with the evidence and confidence behind each score, plus 210 synthetic applicants.
- `DAL_applicant_simulation.ipynb`: the Monte Carlo simulation (10,000 iterations) and the test against my own answers.

Used Python with pandas, NumPy, SciPy, Matplotlib, seaborn and openpyxl.

## Good to know

- Every applicant is synthetic.
- The curriculum scores describe what a degree covers, req skills are based on self evaluation fomr.
- The results are a range, not a prediction of who gets accepted.

Sara Aldamer
