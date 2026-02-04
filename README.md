# DeepMIMODetection for CMDNet

The original DetNet code from [4] was downloaded, modified and resimulated for comparison to CMDNet enabling high reproducibility of PhD thesis [1] and publications [2,3]:
1. Edgar Beck, Advancing Semantic and Digital Communications through Machine Learning, ser. Dissertations from the Department of Communications Engineering, University of Bremen, A. Dekorsy, Ed. Düren: Shaker Verlag, Dec. 2025, vol. 15. https://doi.org/10.26092/elib/4791
2. Edgar Beck, Carsten Bockelmann, and Armin Dekorsy, “CMDNet: Learning a Probabilistic Relaxation of Discrete Variables for Soft Detection With Low Complexity,” IEEE Trans. Commun., vol. 69, no. 12, pp. 8214–8227, Dec. 2021. https://doi.org/10.1109/TCOMM.2021.3114682
3. Edgar Beck, Carsten Bockelmann, and Armin Dekorsy, “Concrete MAP Detection: A Machine Learning Inspired Relaxation,” in 24th International ITG Workshop on Smart Antennas (WSA 2020), vol. 24, Hamburg, Germany, Feb. 2020, pp. 1–5.
4. N. Samuel, T. Diskin, and A. Wiesel, “Deep MIMO Detection,” in 18th IEEE International Workshop on Signal Processing Advances in Wireless Communications (SPAWC 2017), Sapporo, Japan, Jul. 2017, pp. 1–5. https://doi.org/10.1109/SPAWC.2017.8227772

The main files are `DetNet_CMDNet.py` and `load_DetNet_CMDNet.py` besides the original main files.


## DeepMIMODetection (Original)

This repository holds 2 files.

The first one is the FullyConnected architecture used to detect over a fixed channel (in this specific case we detect over a 0.6-Toeplitz channel where K=20 N=30. CSV file with the channel also found in this repo).

The second one is the DetNet architecture as described in the paper "Deep MIMO Detection" presented at SPAWC 2017. Detection is over I.I.D gaussian random channels.

For any further questions regarding the code contact at neev.samuel@gmail.com
