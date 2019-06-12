TEST DATA

To run test data, type the following into the MATLAB command window after downloading RTP-STAR:

RTPSTAR_MAIN(1,[],'genes_file.csv','expression_file.csv','clustering_file.csv','timecourse_file.csv','symbol_file.xlsx',true,1,[])

Your output files will be named "clusters.csv" for the clusters and "biograph_final.txt."

Since we are setting the cluster seed to 1, you should obtain the same clusters (and therefore the same network) each time.

Runtime should be less than 1 minute.