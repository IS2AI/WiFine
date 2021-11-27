# WiFine
A finer-level sequential dataset of WiFi received signal strengths (RSS).
The dataset contains 290 trajectories collected across 3 floors of C4 building of Nazarbayev University.
The RSS values with corresponding position coordinates (x,y,z) are recorded around every 5 seconds.

## Dataset statistics
| #Buildings  | #Floors   | #Wireless access points (WAP) | Area (m<sup>2</sup>)
|:-----------:|:---------:|:-----------------------------:|:--------:
| 1           | 3         | 436                           |9,564

| Sets      |#Trajectories  |#Reference points (RP)   |#Samples   |Total length (m) | Total duration (s)
|:---------:|:-------------:|:-----------------------:|:---------:|:---------------:|:---------:
|Train      |120            |18,975                   |18,975     |≈31,814          |112,321
|Validation |85             |3,034                    |3,034      |≈4,789           |17,280
|Test       |85             |3,781                    |3,781      |≈6,162           |22,116
|**Total**  |**290**        |**25,790**               |**25,790** |**≈42,765**      |**151,717**


## Citation
```bibtex
@inproceedings{khassanov2021finer,
  title={Finer-level Sequential WiFi-based Indoor Localization},
  author={Khassanov, Yerbolat and Nurpeiissov, Mukhamet and Sarkytbayev, Azamat and Kuzdeuov, Askat and Varol, Huseyin Atakan},
  booktitle={2021 IEEE/SICE International Symposium on System Integration (SII)},
  pages={163--169},
  year={2021},
  organization={IEEE}
}
```
