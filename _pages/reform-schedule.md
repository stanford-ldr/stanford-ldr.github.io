---
layout: page
title: REFORM Schedule and Past Meetings
permalink: /reform/schedule/
description: Upcoming and past REFORM sessions, papers, and discussion materials.
_styles: |
  .reform-table-wrap {
    overflow: auto;
    border: 1px solid var(--global-divider-color);
    border-radius: 0.75rem;
    background: var(--global-card-bg-color);
  }

  .reform-schedule-table {
    width: 100%;
    min-width: 900px;
    margin: 0;
    border-collapse: collapse;
  }

  .reform-schedule-table th,
  .reform-schedule-table td {
    text-align: left;
    vertical-align: top;
    padding: 0.75rem 0.9rem;
    border-bottom: 1px solid var(--global-divider-color);
  }

  .reform-schedule-table thead th {
    background: color-mix(in srgb, var(--global-bg-color) 88%, var(--global-theme-color));
    font-weight: 700;
    border-bottom: 2px solid var(--global-divider-color);
  }

  .reform-schedule-table th {
    white-space: nowrap;
  }

  .reform-schedule-table tr:last-child td {
    border-bottom: none;
  }

  .reform-schedule-table .reform-break td {
    font-weight: 600;
    text-align: center;
    background: color-mix(in srgb, var(--global-bg-color) 90%, var(--global-theme-color));
    color: var(--global-text-color-light);
  }
---

Meetings are held every Thursday at 5 PM (CoDa W101).

A list of topics, suggested reading, and session plans is available [here](https://docs.google.com/spreadsheets/d/14ChmArQCa4wlQ3vE7taNzmzd96d0N_a7XaJOgaDPunU/edit?gid=0#gid=0).

Sign up to be a discussant [here](https://tinyurl.com/reform-ml-signup-w26). Goal(s) of the discussant group:

- Prepare a 20–30 minute presentation, accessible to a second-year PhD student, focusing on (a) seeding discussion, (b) identifying gaps and connections, and (c) formulating open problems
- We suggest several papers for each week—more than one can cover thoroughly in a week. Pick a small, focused set of papers and read them thoroughly
- Do a single “deep dive” per week about one subject (this can span multiple papers)

Signing up is a great way to (1) force yourself to engage with the content of the paper, (2) get to know your co-discussant(s), and (3) ensure the success of the reading group.

## Upcoming & Past Sessions

<div class="reform-table-wrap">
  <table class="reform-schedule-table">
    <thead>
      <tr>
        <th>Date</th>
        <th>Topic</th>
        <th>Resources</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>2024-10-16</td>
        <td>Introduction</td>
        <td><a href="{{ '/assets/reform/FirstMeetingSlides.pdf' | relative_url }}">Slides</a></td>
      </tr>
      <tr>
        <td>2024-10-23</td>
        <td>Scaling Laws 1 (Training Compute-Optimal Language Models)</td>
        <td><a href="https://arxiv.org/abs/2203.15556">Paper</a> <a href="{{ '/assets/reform/Meeting1-ChinchillaPaper-Slides.pdf' | relative_url }}">Slides</a></td>
      </tr>
      <tr>
        <td>2024-10-30</td>
        <td>Scaling Laws 2 (Explaining Neural Scaling Laws)</td>
        <td><a href="https://arxiv.org/abs/2102.06701">Paper</a> <a href="{{ '/assets/reform/TheoryScalingSlides.pdf' | relative_url }}">Slides</a></td>
      </tr>
      <tr>
        <td>2024-11-06</td>
        <td>Data Selection 1 (Perplexity Correlations, Scaling Laws + Data Filtering)</td>
        <td><a href="https://arxiv.org/abs/2409.05816">Paper 1</a> <a href="https://arxiv.org/abs/2404.07177">Paper 2</a> <a href="{{ '/assets/reform/DataSelection1.pdf' | relative_url }}">Slides</a></td>
      </tr>
      <tr>
        <td>2024-11-13</td>
        <td>Data Selection 2 (DsDm, LESS)</td>
        <td><a href="https://arxiv.org/abs/2401.12926">Paper 1</a> <a href="https://arxiv.org/abs/2402.04333">Paper 2</a> <a href="https://ml-data-tutorial.org/">Tutorial</a> <a href="{{ '/assets/reform/DataAttributionSlides.pdf' | relative_url }}">Slides (DsDm)</a> <a href="{{ '/assets/reform/LESSSlides.pdf' | relative_url }}">Slides (LESS)</a></td>
      </tr>
      <tr>
        <td>2024-11-20</td>
        <td>Data Selection 3 (Statistical Theory)</td>
        <td><a href="https://arxiv.org/abs/2309.14563">Paper</a> <a href="{{ '/assets/reform/DataSelection3.pdf' | relative_url }}">Slides</a></td>
      </tr>
      <tr>
        <td>2024-11-20</td>
        <td>Data Selection 3 (Pruning, Prediction)</td>
        <td><a href="https://arxiv.org/abs/2206.14486">Paper 1</a> <a href="https://arxiv.org/abs/2210.01072">Paper 2</a></td>
      </tr>
      <tr>
        <td>2025-01-22</td>
        <td>Post-training 1 (RLHF, AlpacaFarm)</td>
        <td><a href="https://arxiv.org/abs/2203.02155">Paper 1</a> <a href="https://arxiv.org/abs/2305.14387">Paper 2</a> <a href="{{ '/assets/reform/PostTraining-1.pdf' | relative_url }}">Slides</a></td>
      </tr>
      <tr>
        <td>2025-01-29</td>
        <td>No meeting (ICML Deadline)</td>
        <td></td>
      </tr>
      <tr>
        <td>2025-02-05</td>
        <td>Post-training 2 (Direct methods &amp; Offline RL)</td>
        <td><a href="https://arxiv.org/abs/2305.18290">Paper 1</a> <a href="https://arxiv.org/abs/2410.08847">Paper 2</a> <a href="https://arxiv.org/abs/2406.01462">Paper 3</a> <a href="https://arxiv.org/abs/2405.08448">Paper 4</a> <a href="{{ '/assets/reform/RL-1.pdf' | relative_url }}">Slides 1</a> <a href="{{ '/assets/reform/RL-2.pdf' | relative_url }}">Slides 2</a></td>
      </tr>
      <tr>
        <td>2025-02-12</td>
        <td>Post-training 3 (DeepSeek)</td>
        <td><a href="https://github.com/deepseek-ai/DeepSeek-R1/blob/main/DeepSeek_R1.pdf">Paper</a> <a href="{{ '/assets/reform/DeepSeek-Slides.pdf' | relative_url }}">Slides</a></td>
      </tr>
      <tr>
        <td>2025-02-19</td>
        <td>Post-training 4 (Synthetic Data)</td>
        <td><a href="{{ '/assets/reform/SyntheticData.pdf' | relative_url }}">Slides</a></td>
      </tr>
      <tr>
        <td>2025-02-26</td>
        <td>Post-training 4 (Synthetic Data &amp; Self-Improvement)</td>
        <td><a href="https://arxiv.org/abs/2404.01413">Paper 1</a> <a href="https://arxiv.org/abs/2502.01612">Paper 2</a> <a href="{{ '/assets/reform/SyntheticData-2.pdf' | relative_url }}">Slides</a></td>
      </tr>
      <tr>
        <td>2025-03-04</td>
        <td>Post-training 5 (Simplicity)</td>
        <td><a href="https://arxiv.org/abs/2501.19393">Paper 1</a> <a href="https://arxiv.org/abs/2409.14254">Paper 2</a> <a href="{{ '/assets/reform/InstructionFollowing.pdf' | relative_url }}">Slides</a></td>
      </tr>
      <tr>
        <td>2025-03-11</td>
        <td>Post-training 5 (In-Context Learning)</td>
        <td><a href="{{ '/assets/reform/ICLSurvey.pdf' | relative_url }}">Slides</a></td>
      </tr>
      <tr class="reform-break">
        <td colspan="3">(Between-quarter break)</td>
      </tr>
      <tr>
        <td>2025-04-09</td>
        <td>Reasoning 1 (Introduction)</td>
        <td><a href="{{ '/assets/reform/REFORMFirstMeeting-Spring2025.pdf' | relative_url }}">Slides</a></td>
      </tr>
      <tr>
        <td>2025-04-16</td>
        <td>Reasoning 2 (STaR)</td>
        <td><a href="https://arxiv.org/abs/2203.14465">Paper</a></td>
      </tr>
      <tr>
        <td>2025-04-23</td>
        <td>Reasoning 3 (Process rewards)</td>
        <td><a href="{{ '/assets/reform/ProcessRewards.pdf' | relative_url }}">Slides</a> <a href="http://arxiv.org/abs/2211.14275">Paper 1</a> <a href="https://arxiv.org/abs/2305.20050">Paper 2</a></td>
      </tr>
      <tr>
        <td>2025-04-30</td>
        <td>Reasoning 4 (More Self-improvement)</td>
        <td><a href="https://arxiv.org/abs/2210.11610">Paper</a></td>
      </tr>
      <tr class="reform-break">
        <td colspan="3">(Summer break)</td>
      </tr>
      <tr>
        <td>2025-10-09</td>
        <td>Post-deployment/Safety 1 (CoT Monitoring)</td>
        <td><a href="https://arxiv.org/abs/2505.05410">Paper 1</a> <a href="https://arxiv.org/abs/2507.05246">Paper 2</a> <a href="{{ '/assets/reform/REFORMFirstMeeting-Fall2025.pdf' | relative_url }}">Slides</a></td>
      </tr>
      <tr>
        <td>2025-10-16</td>
        <td>Post-deployment/Safety 2 (Jailbreaking, Elicitation)</td>
        <td><a href="https://arxiv.org/abs/2010.15980">Paper 1</a> <a href="https://arxiv.org/abs/2307.15043">Paper 2</a> <a href="https://arxiv.org/abs/2502.01236">Paper 3</a> <a href="{{ '/assets/reform/Prompting.pdf' | relative_url }}">Slides</a></td>
      </tr>
      <tr>
        <td>2025-10-23</td>
        <td>Post-deployment/Safety 3 (Hallucinations)</td>
        <td><a href="https://arxiv.org/abs/2509.04664">Paper 1</a> <a href="https://arxiv.org/abs/2507.16806">Paper 2</a> <a href="{{ '/assets/reform/Hallucinations.pdf' | relative_url }}">Slides 1</a> <a href="{{ '/assets/reform/RLCR.pdf' | relative_url }}">Slides 2</a></td>
      </tr>
      <tr>
        <td>2025-10-30</td>
        <td>Post-deployment/Safety 3 (Privacy and Memorization)</td>
        <td><a href="{{ '/assets/reform/Privacy1.pdf' | relative_url }}">Slides 1</a> <a href="{{ '/assets/reform/Privacy2.pdf' | relative_url }}">Slides 2</a> <a href="https://arxiv.org/abs/1802.08232">Paper 1</a> <a href="https://arxiv.org/abs/2012.07805">Paper 2</a></td>
      </tr>
      <tr>
        <td>2025-11-06</td>
        <td>Post-deployment/Safety 4 (Emergent Misalignment)</td>
        <td><a href="https://arxiv.org/abs/2502.17424">Paper</a></td>
      </tr>
      <tr>
        <td>2025-11-13</td>
        <td>Post-deployment/Safety 5 (Out-of-Context Reasoning)</td>
        <td><a href="{{ '/assets/reform/OOCReasoning.pdf' | relative_url }}">Slides</a> <a href="https://arxiv.org/abs/2309.00667">Paper 1</a> <a href="https://arxiv.org/abs/2406.14546">Paper 2</a> <a href="https://arxiv.org/abs/2412.04614">Paper 3</a> <a href="https://arxiv.org/abs/2506.10887">Paper 4</a></td>
      </tr>
      <tr>
        <td>2026-01-22</td>
        <td>Introduction + Sharpness and Training Dynamics 1 (Edge of Stability)</td>
        <td><a href="{{ '/assets/reform/EOS.pdf' | relative_url }}">Slides</a> <a href="https://arxiv.org/abs/2103.00065">Paper</a> <a href="https://arxiv.org/abs/2209.15594">Extra Reading 1</a> <a href="https://arxiv.org/abs/2207.12678">Extra Reading 2</a></td>
      </tr>
      <tr>
        <td>2026-02-05</td>
        <td>Sharpness and Training Dynamics 2 (Sharpness-Aware Minimization)</td>
        <td><a href="{{ '/assets/reform/05_02_2026_SAM_1.pdf' | relative_url }}">Slides 1</a> <a href="{{ '/assets/reform/05_02_2026_SAM_2.pdf' | relative_url }}">Slides 2</a> <a href="https://arxiv.org/abs/2010.01412">Paper 1</a> <a href="https://arxiv.org/abs/2302.07011">Paper 2</a></td>
      </tr>
      <tr>
        <td>2026-02-12</td>
        <td>Overfitting and Generalization 1: Double Descent</td>
        <td><a href="{{ '/assets/reform/12_02_2026_Double_Descent_1.pdf' | relative_url }}">Slides 1</a> <a href="{{ '/assets/reform/12_02_2026_Double_Descent_2.pdf' | relative_url }}">Slides 2</a> <a href="https://arxiv.org/abs/1912.02292">Paper 1</a> <a href="https://arxiv.org/abs/1908.05355">Paper 2</a></td>
      </tr>
      <tr>
        <td>2026-02-19</td>
        <td>Overfitting and Generalization 2: Benign Overfitting</td>
        <td><a href="{{ '/assets/reform/19_02_2026_Benign%20Overfitting_1.pdf' | relative_url }}">Slides 1</a> <a href="{{ '/assets/reform/19_02_2026_Benign%20Overfitting_2.pdf' | relative_url }}">Slides 2</a> <a href="https://arxiv.org/abs/1906.11300">Paper 1</a> <a href="https://arxiv.org/abs/2502.07480">Paper 2</a></td>
      </tr>
      <tr>
        <td>2026-02-26</td>
        <td>Emergent Abilities 1: Grokking</td>
        <td><a href="https://arxiv.org/abs/2301.05217">Paper 1</a> <a href="https://arxiv.org/abs/2402.15175">Paper 2</a></td>
      </tr>
    </tbody>
  </table>
</div>
