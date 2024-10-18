
[![arXiv][paper-shield]][paper-url]
[![MIT License][license-shield]][license-url]
[![hf][hfmodel-shield]][hfmodel-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <!-- <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a> -->

  <h3 align="center">TinyClick: Single-Turn Agent for Empowering GUI Automation</h3>

  <p align="center">
    The code for running the model from paper: TinyClick: Single-Turn Agent for Empowering GUI Automation
  </p>
</div>


<!-- ABOUT THE PROJECT -->
## About The Project

We present a single-turn agent for graphical user interface (GUI) interaction tasks, using Vision-Language Model Florence-2-Base. Main goal of the agent is to click on desired UI element based on the screenshot and user command. It demonstrates strong performance on Screenspot and OmniAct, while maintaining a compact size of 0.27B parameters and minimal latency.


<!-- INSTALLATION -->
## Installation

Before running, set up the environment and install the required packages:

```pip install -r requirements.txt```


<!-- USAGE EXAMPLES -->
## Usage

To see example inference with TinyClick, run this command:<br />
```python3 main.py --image-path "<PATH>" --text "<COMMAND>"```


<!-- CITATION -->
## Citation

```
@misc{pawlowski2024tinyclicksingleturnagentempowering,
    title={TinyClick: Single-Turn Agent for Empowering GUI Automation}, 
    author={Pawel Pawlowski and Krystian Zawistowski and Wojciech Lapacz and Marcin Skorupa and Adam Wiacek and Sebastien Postansque and Jakub Hoscilowicz},
    year={2024},
    eprint={2410.11871},
    archivePrefix={arXiv},
    primaryClass={cs.HC},
    url={https://arxiv.org/abs/2410.11871}, 
}
```


<!-- LICENSE -->
## License

Please check the MIT license that is listed in this repository. See `LICENSE` for more information.


<!-- MARKDOWN LINKS & IMAGES -->
[paper-shield]: https://img.shields.io/badge/2024-arXiv-red
[paper-url]: https://arxiv.org/abs/2410.11871
[license-shield]: https://img.shields.io/badge/License-MIT-yellow.svg
[license-url]: https://opensource.org/licenses/MIT
[hfmodel-shield]: https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Model-blue
[hfmodel-url]: https://huggingface.co/Samsung/TinyClick