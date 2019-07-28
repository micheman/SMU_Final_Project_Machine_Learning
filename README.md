# SMU_Final_Project_Machine_Learning

Final Project repository. All code, data and documentation for the Real Estate Market Price Estimator

Full documentation can be found in \documentation: Final Project Report.docx & FinalPresentationPPT.pptx

How To Run The Model

1.	Place the following files into a common directory “Path”>
    a.	rempest_cmd.py
    b.	0smallListings.pkl
    c.	random_forest_model.joblib

2.	Execute at the command prompt “Path”>
    a.	“Path”> python rempest_cmd.py C:\> python rempest_cmd.py <Beds> <Baths> <HlfBath> <Gar>\
                                      <TCP> <YB> <Pool: yes = 1, no = 0> <Square Feet> <Acres>
    b.	After processing, resulting output will appear: [Estimated Home Price]
