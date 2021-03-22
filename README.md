<img src="assets/firewall.png" width=65% raw="true" alt="For a better Classification of Bacteria Digital Image using Deep Learning"/>

 
# Intrusion Detection System (IDS)

Academic research in the field of **Deep Learning**

## The Dataset:

This project made use of the CIC-IDS-2017, found here:https://www.unb.ca/cic/datasets/ids-2017.html .
'BENIGN', 'Web Attack \x96 Brute Force', 'Web Attack \x96 XSS',
       'Web Attack \x96 Sql Injection', 'Bot', 'FTP-Patator',
       'SSH-Patator', 'DDoS', 'PortScan', 'Infiltration', 'DoS slowloris',
       'DoS Slowhttptest', 'DoS Hulk', 'DoS GoldenEye', 'Heartbleed'

<table>
  <tr>
    <th>#</th>
    <th>Profile</th>
    <th>Count</th>
  </tr>

  <tr>
    <td>1</td>
    <td>Benign</td>
    <td>20</td>
  </tr>

  <tr>
    <td>2</td>
    <td>Web Attack Brute Force</td>
    <td>22</td>
  </tr>

  <tr>
    <td>3</td>
    <td>Web Attack XSS</td>
    <td>23</td>
  </tr>

  <tr>
    <td>4</td>
    <td>Web Attack Sql Injection</td>
    <td>22</td>
  </tr>

  <tr>
    <td>5</td>
    <td>Bot</td>
    <td>20</td>
  </tr>

  <tr>
    <td>6</td>
    <td>FTP-Patato</td>
    <td>20</td>
  </tr>

  <tr>
    <td>7</td>
    <td>SSH-Patatori</td>
    <td>20</td>
  </tr>

  <tr>
    <td>8</td>
    <td>DDoS</td>
    <td>20</td>
  </tr>

  <tr>
    <td>9</td>
    <td>PortScan</td>
    <td>23</td>
  </tr>

  <tr>
    <td>10</td>
    <td>Infiltration</td>
    <td>23</td>
  </tr>

  <tr>
    <td>11</td>
    <td>DoS slowloris</td>
    <td>20</td>
  </tr>

  <tr>
    <td>12</td>
    <td>DoS Slowhttptest</td>
    <td>20</td>
  </tr>

  <tr>
    <td>13</td>
    <td>DoS Hulk</td>
    <td>20</td>
  </tr>

  <tr>
    <td>14</td>
    <td>DoS GoldenEye</td>
    <td>23</td>
  </tr>

  <tr>
    <td>15</td>
    <td>Heartbleed</td>
    <td>23</td>
  </tr>

  <tr>
    <td colspan="2" style="text-align:center"><b>Total</b></td>
    <td><b>689</b></td>
  </tr>
</table>
 
## The Model:
the architecture has been devolop by uasing hyper parameter tuning feature of keras library. A Stratified-5-Folds cross validation was used to validate the performance of the model, An average of **99.87%** accuracy has been achieved, competing and even beating published State-of-The-Art models. The Keras library was used with Tensorflow backend.

<img src="assets/model.png" raw="true" alt="For a better Intrusion Detection System using Deep Learning"/>

The accuracy of the folds..
|Fold|Validation accuracy (%)|
|:---:|:---:|
|Fold-1 |99.97%|
|Fold-2 |99.98%|
|Fold-3 |99.96%|
|Fold-4 |99.47%|
|Fold-5 |99.96%|
|**Average**|**99.87%**|

A. Alaodat: **For-a-better-Intrusion-Detection-System-using-Deep-Learning**
