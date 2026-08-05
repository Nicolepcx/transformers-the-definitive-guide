⭐ If you find this repository helpful, please consider giving it a ⭐ here on GitHub (click the star button in the top right corner) 
It's a quick way to show support for this openly available code. ⭐

![OReilly_logo_rgb.png](resources%2FOReilly_logo_rgb.png)

# Transformers - The definitive Guide
This is the corresponding code for the book Transformers - The definitive Guide
The book can be found [here](https://oreillymedia.pxf.io/ZQOjdW)

## TOC
- Chapter 1 From First Principles to State-of-the-Art Transformers
- Chapter 2 Transformers for Time Series
- Chapter 3 Transformers for Vision Tasks
- Chapter 4 Transformers for Image Generation
- Chapter 5 Transformers for Video Generation
- Chapter 6 Transformers for Audio Tasks 
- Chapter 7 Reinforcement Learning Transformers 
- Chapter 8 Transformers for Planing, Reasoning and Coding
- Chapter 9 AI Agents for Complex Tasks 
- Chapter 10 Optimizing Transformer for Problem Solving
- Chapter 11 Deploying transformer models
- Chapter 12 Where to go next

## Instructions and Navigation
All of the code is organized into folders. Each folder starts with `CH` followed by the chapter number. For example, CH01.
The notebooks are then organized as follows: `ch01_attention_mechanism_variations.ipynb`, where `ch01` indicates the chapter
and `attention_mechanism_variations` what is done in the notebook. 


## Repo structure

```
├── LICENSE
├── README.md             <- The top-level README for developers using this project.
├── CH01                  <- Per chapter folder with Jupyter notebooks.
    ├── [name].ipynb      <- Jupyter notebooks with naming as mentioned above.
├── CH02                  <- Per chapter folder with Jupyter notebooks.
...                       <- Same structure for all chapters.
├── utils                 <- Custom classes and functions and utility functions.
├── resources             <- Some miscellaneous resources.

```


## Virtual Envrionment

The provided bash script `create_env.sh` automates the process of creating a Python virtual environment using either conda or pipenv, 
installing the required packages from a `requirements.txt file`. To use the script run `bash create_env.sh` in your 
terminal on Microsoft Windows (with WSL), Apple macOS, or Linux operating systems.

<span style="color:red">
NOTE: A virtual environment is not necessary for the notebooks in this repository, as they are designed to be run on a cloud service with GPU support. Therefore, the provided instructions for creating a virtual environment are more for reference and general guidance than a strict requirement. </span>

## Running the Notebooks

Every notebook can be opened and run on Google Colab directly from the links below. Just click the **Open In Colab** badge next to the notebook you want to run.

### Chapter 1 — From First Principles to State-of-the-Art Transformers
| Notebook | Colab |
|---|---|
| Attention Mechanism Variations | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH01/ch01_attention_mechanism_variations.ipynb) |
| Embeddings | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH01/ch01_embeddings.ipynb) |
| Perplexity | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH01/ch01_perplexity.ipynb) |

### Chapter 2 — Transformers for Time Series
| Notebook | Colab |
|---|---|
| Chronos | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH02/ch02_Chronos.ipynb) |
| PatchTST Hyperparameters (IBM, 10 Days Ahead, 32 Context Window) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH02/ch02_patch_tst_hyperparameter_IBM_10_days_ahead_32_context_window.ipynb) |
| Time Series Fine-Tuning (PyTorch) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH02/ch02_time_series_finetuning_torch.ipynb) |

### Chapter 3 — Transformers for Vision Tasks
| Notebook | Colab |
|---|---|
| Fine-tune SAM with W&B + Optuna | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH03/ch03_Fine_tune_SAM_with_wandb_optuna.ipynb) |
| ViT Embeddings & Tokens | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH03/ch03_ViT_embeddings_tokens.ipynb) |
| Image Classification | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH03/ch03_image_classification.ipynb) |
| Segment Videos with SAM 2 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH03/ch03_segment_videos_with_sam2.ipynb) |

### Chapter 4 — Transformers for Image Generation
| Notebook | Colab |
|---|---|
| DiT | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH04/ch04_Dit.ipynb) |
| KV Compression | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH04/ch04_KV_compression.ipynb) |
| PixArt-Σ XL Inference | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH04/ch04_inference_PixArt_Sigma_XL.ipynb) |
| Quantize Text-to-Image Models | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH04/ch04_quantize_T2I_models.ipynb) |

### Chapter 5 — Transformers for Video Generation
| Notebook | Colab |
|---|---|
| LTX | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH05/ch05_LTX.ipynb) |
| Latte | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH05/ch05_latte.ipynb) |
| Tora | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH05/ch05_tora.ipynb) |

### Chapter 6 — Transformers for Audio Tasks
| Notebook | Colab |
|---|---|
| Kimi-Audio Meeting Transcription | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH06/ch06_Kimi_audio_transcribe_meeting.ipynb) |
| Qwen2-Audio Audio Tasks | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH06/ch06_Qwen2_Audio_different_audio_tasks.ipynb) |
| SAM Audio | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH06/ch06_SAM_audio.ipynb) |
| Music Generation | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH06/ch06_music_generation.ipynb) |
| Waveforms & Spectrogram Plots | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH06/ch06_wave_and_spectograms_plots.ipynb) |

### Chapter 7 — Reinforcement Learning Transformers
| Notebook | Colab |
|---|---|
| STORM | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH07/ch07_STORM.ipynb) |
| Decision Transformer | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH07/ch07_decision_transformer.ipynb) |
| Replay Buffer (Decision Transformer) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH07/ch07_replay_buffer_DT.ipynb) |

### Chapter 8 — Transformers for Planning, Reasoning and Coding
| Notebook | Colab |
|---|---|
| Qwen3 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH08/ch08_Qwen3.ipynb) |
| Rethink MCTS | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH08/ch08_Rethink_MCTS.ipynb) |
| TreeQuest | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH08/ch08_TreeQuest.ipynb) |
| Kimi K2 Instruct | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH08/ch08_kimi_k2_instruct.ipynb) |

### Chapter 9 — AI Agents for Complex Tasks
| Notebook | Colab |
|---|---|
| LangGraph Multi-turn Conversation | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH09/09_langgraph_multiturn_conversation.ipynb) |
| Market Research Team (LangGraph Multi-Agent) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH09/ch09_market_research_team_LangGraph_multi_agent.ipynb) |

### Chapter 10 — Optimizing Transformers for Problem Solving
| Notebook | Colab |
|---|---|
| AdaptThink | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH10/ch10_AdaptThink.ipynb) |
| ART·E with LangGraph | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH10/ch10_art_e_langgraph.ipynb) |
| rLLM | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH10/ch10_rLLM.ipynb) |

### Chapter 11 — Deploying Transformer Models
| Notebook | Colab |
|---|---|
| LLM Performance Evaluation | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH11/ch11_LLM_performance_evaluation.ipynb) |
| Advanced LoRA Fine-Tuning | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH11/ch11_advanced_LoRA_fine_tuning.ipynb) |
| LangGraph Code Interpreter | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH11/ch11_langgraph_code_interpreter.ipynb) |

### Chapter 12 — Where to Go Next
| Notebook | Colab |
|---|---|
| SAM 3 Agent | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/transformers-the-definitive-guide/blob/master/CH12/ch12_sam3_agent.ipynb) |


Each notebook is connected with this Github repo, meaning by running a notebook, it will automatically clone the repo, so you can easily access all resources outside the notebook.
Like customs functions and classes as well as utility functions to automatically install the requirements per chapter: 


```
!git clone https://github.com/Nicolepcx/transformers-the-definitive-guide

current_path = %pwd
if '/transformers-the-definitive-guide' in current_path:
    new_path = current_path + '/utils'
else:
    new_path = current_path + '/transformers-the-definitive-guide/utils'
%cd $new_path
```
__NOTE:__ You need to run the notebooks with a GPU. 
