# CWC-19-Points-Table-Structure-Using-MATLAB-
This is the points and statistics table for the Cricket World Cup (Mens) that occurred in 2019 
This has been achieved using MATLAB (please use .mlx whilst opening)

% This structure table shows the points table for all the teams in the
% Cricket World Cup 2019

England = struct('wins', 6, 'losses', 3, 'Ties', 0, 'NR', 0, 'NRR', 1.152, 'Pts', 12);
New_Zealand = struct('wins', 5, 'losses', 3, 'Ties', 0, 'NR', 1, 'NRR', 0.175, 'Pts', 11);
Australia = struct('wins', 7, 'losses', 2, 'Ties', 0, 'NR', 0, 'NRR', 0.868, 'Pts', 14);
India = struct('wins', 7, 'losses', 1, 'Ties', 0, 'NR', 1, 'NRR', 0.809, 'Pts', 15);
Pakistan = struct('wins', 5, 'losses', 3, 'Ties', 0, 'NR', 1, 'NRR', -0.430, 'Pts', 11);
Sri_Lanka = struct('wins', 3, 'losses', 4, 'Ties', 0, 'NR', 2, 'NRR', -0.919, 'Pts', 8);
West_Indies = struct('wins', 2, 'losses', 6, 'Ties', 0, 'NR', 1, 'NRR', -0.225, 'Pts', 5);
South_Africa = struct('wins', 3, 'losses', 5, 'Ties', 0, 'NR', 1, 'NRR', -0.030, 'Pts', 7);
Bangladesh = struct('wins', 3, 'losses', 5, 'Ties', 0, 'NR', 1, 'NRR', -0.410, 'Pts', 7);
Afghanistan = struct('wins', 0, 'losses', 9, 'Ties', 0, 'NR', 0, 'NRR',-1.322, 'Pts', 0);


% Please input the country's name exactly as it is shown above in order to
% get all the statistics regarding that country's performance
Country_Name = input('please input one of the 10 countries')


