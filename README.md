**Note:** _Modify this README as appropriate. If this is a NASA-funded project, edit the LICENSE and remove the Copyright notice at the top. Then remove this Note and check in the changes to your repository._

![NSIDC logo](/images/NSIDC_logo_2018_poster-1.png)


# NSIDC MyArcticTool

The NSIDC Daily Arctic Sea Ice Extent tool is designed for users to be able to Visualize MASIE, Sea Ice Index, and Near Real Time CDR data sets.

## Level of Support

_(Choose one of the following bullets to describe USO Level of Support, then delete this instructional message along with the unchosen support bullet)_

* This repository is not actively supported by NSIDC but we welcome issue submissions and pull requests in order to foster community contribution.

See the [LICENSE](LICENSE) for details on permissions and warranties. Please contact nsidc@nsidc.org for more information.

## Requirements

This package requires:
* Pandas, numpy, matplotlib.pyplot, os, urllib.request, and calendar Python libraries
* Data from MASIE (ID G02186), Sea Ice Index (ID G02135), Near Real Time CDR (ID G10016) found at the NSIDC website

## Installation
This code can be downloaded and run completely in Python or Jupyter Notebook

## Usage

After downloading and formatting the code for your machine, simply input the date range of interest and run the code. The output can be customized to visualize all three together, seperately or a variation of which data sets you would like to see.

## Troubleshooting
* It is very important to ensure all data set sources are in one directory and that the code is set to see that directory. 
* This code was created using a Windows machine, so there may be some minor formatting changes to be made like direction of slashes in the directory definition. 
* The date range input format is variable, ensure you are using the correct format for the correct data set; MASIE is m/d/yyyy, Sea Ice Index is yyyy-mm-dd, and NRT CDR is m/d/yyyy. 
* The Masie data set has known 'holes' in the data. This means that before running the code, you will need to reformat this data either by hand, or overwrite the code to allow for skips in data. The updated list for missing data (in a .txt file) can be found at https://nsidc.org/data/g02186?qt-data_set_tabs=2#qt-data_set_tabs under "Detailed Data Description" subcategory "Data Access"

## License

See [LICENSE](LICENSE).

## Code of Conduct

See [Code of Conduct](CODE_OF_CONDUCT.md).

## Credit

This software was developed by Michaela Sizemore for the National Snow and Ice Data Center under the supervision of Florence Fetterer with help from Ann Windnagel 
