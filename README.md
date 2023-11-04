# Real-time Animation Generation and Control on Rigged Models via Large Language Models
 
This repository serves as a showroom for various animations generated by large language models (LLM) with the approach described in

> Huang, Han, et al. "Real-time Animation Generation and Control on Rigged Models via Large Language Models." arXiv preprint arXiv:2310.17838 (2023).
> [[arXiv]](https://arxiv.org/abs/2310.17838)

Our method takes a rigged 3D model and produces novel animations with natural language descriptions in a matter of seconds. Currently, there are multiple limitations in robustness and excess token usage for complex joint hierarchies. However, it is fascinating that LLMs can manage this at all!

## Animation Generation

The quoted texts are the prompts used to generate the animation.

### Few-shot

| <img src="/videos/whale_head_moving.gif" width="375" height="200"/>| <img src="/videos/whale_swim_aggressively.gif" width="375" height="200"/> |
| :-------------: | :-------------: | 
| "Tilting its head" for a whale  | "Swimming aggressively" for a whale |

| <img src="/videos/whale_tail_flap.gif" width="375" height="200"/>| <img src="/videos/whale_attempting_to_fly.gif" width="375" height="200"/> |
| :-------------: | :-------------: | 
| "Flapping its tail" for a whale  | "Attempting to fly like a bird" for a whale |

| <img src="/videos/pig_eat.gif" width="300" height="300"/> | <img src="/videos/pig_jump.gif" width="400" height="300"/>  |
| :-------------: | :-------------: | 
| "Eating" for a pig | "Jumping" for a pig |

| <img src="/videos/raccoon_disapproval.gif" width="350" height="400"/>| <img src="/videos/raccoon_bow.gif" width="350" height="400"/>  |
| :-------------: | :-------------: | 
| "Showing disapproval" for a raccoon | "Bowing" for a raccoon  |

### Zero-shot

| <img src="/videos/bird_flying_high_and_low.gif" width="200" height="150"/> |  <img src="/videos/stickman_cheering.gif" width="150" height="150"/> | <img src="/videos/person_jumping.gif" width="250" height="150"/>  |
| :-------------: | :-------------: | :-------------: | 
| "Flying high and low" for a bird | "Cheering" for a stickman  | "Jumping" for a person  |


## Animation Control

https://github.com/Whalefishin/LLM_animation/assets/21124870/6523ca9e-3f26-4b34-beeb-9a1c61f60eb5

