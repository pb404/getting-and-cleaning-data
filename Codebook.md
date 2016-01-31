DATA DICTIONARY-TINYDATA

SUBJECT    Single-digit integer

        (1,2,3…30):Denotes the number of the subject who participated in the study.

ACTIVITY    Factor with 6 levels

        1.Walking

        2.Walking\_Upstairs

        3.Walking\_Downstairs

        4.Lying

        5.Sitting

        6.Standing

        Denotes the activity for which the variables were calculated.



VARIABLES

        The first term(The term before the first period(.)) denotes the domain:

        1.Time domain

2.Frequency Domain(obtained after taking the fast fourier transform of the relevant value)

The following variables are in the time domain:

COLUMNS[3-8]

Denotes the mean or the standard deviation of the acceleration of the body in the specified direction.

Example: Time.Acceleration of the Body.Mean.X direction denotes the mean of the acceleration of the body in time domain in X direction.



COLUMNS [9-14]

Denotes the mean or the standard deviation of the gravitational acceleration(acceleration due to gravity) of the body in the specified direction.

Example:Time.Gravitational Acceleration .Mean.Z direction denotes the mean of acceleration due to gravity experienced by the smartphone in time domain in the Z direction.

COLUMNS [15-20]

Denotes the mean or the standard deviation of the jerk of acceleration (ie. Sudden change in acceleration) of the body in the specified direction.

Example:Time.Acceleration of Body.Jerk.Standard Deviation .Y direction denotes the standard deviation of the jerk of acceleration experienced by the smartphone in time domain in the Y direction.



COLUMNS [21-26]

Denotes the mean or the standard deviation of the gyroscopic acceleration (acceleration due to rotation) of the body in the specified direction.

Example:Time.Gyroscopic acceleration of Body.Standard Deviation .Y direction denotes the standard deviation of the gyroscopic acceleration experienced by the smartphone in time domain in the Y direction.



COLUMNS [27-32]

Denotes the mean or the standard deviation of the jerk of gyroscopic acceleration (ie. Sudden change in "rotational" acceleration) of the body in the specified direction.

Example:Time.Gyroscopic acceleration of Body.Jerk.Standard Deviation .Y direction denotes the standard deviation of the jerk of gyroscopic acceleration experienced by the smartphone in time domain in the Y direction.

The magnitude of the above signals was calculated using Euclidean Norm and has been recorded in the following columns:

COLUMNS [33-34]

Denotes the mean or the standard deviation of the magnitude of acceleration of the body.



COLUMNS [35-36]

Denotes the mean or the standard deviation of the magnitude of acceleration due to gravity of the body.



COLUMNS [37-38]

Denotes the mean or the standard deviation of the magnitude of jerk of acceleration due to gravity of the body.

COLUMNS [39-40]

Denotes the mean or the standard deviation of the magnitude of the gyroscopic acceleration of the body.

COLUMNS [41-42]

Denotes the mean or the standard deviation of the magnitude of the jerk of gyroscopic acceleration of the body.



The following variables are in the frequency domain:

COLUMNS [43-48]

Denotes the mean or the standard deviation of the acceleration of the body in the specified direction.

Example: Frequency.Acceleration of the Body.Mean.X direction denotes the mean of the acceleration of the body in frequency domain in X direction.

COLUMNS [49-54]

Denotes the mean or the standard deviation of the jerk of acceleration (ie. Sudden change in acceleration) of the body in the specified direction.

Example:Frequency.Acceleration of Body.Jerk.Standard Deviation .Y direction denotes the standard deviation of the jerk of acceleration experienced by the smartphone in frequency domain in the Y direction.



COLUMNS [55-60]

Denotes the mean or the standard deviation of the gyroscopic acceleration (acceleration due to rotation) of the body in the specified direction.

Example:Frequency.Gyroscopic acceleration of Body.Standard Deviation .Y direction denotes the standard deviation of the gyroscopic acceleration experienced by the smartphone in frequency domain in the Y direction.







The magnitude of the above signals was calculated using Euclidean Norm and has been recorded in the following columns:

COLUMNS [61-62]

Denotes the mean or the standard deviation of the magnitude of acceleration of the body.



COLUMNS [63-64]

Denotes the mean or the standard deviation of the magnitude of jerk of acceleration due to gravity of the body.

COLUMNS [65-66]

Denotes the mean or the standard deviation of the magnitude of the gyroscopic acceleration of the body.

COLUMNS [67-68]

Denotes the mean or the standard deviation of the magnitude of the jerk of gyroscopic acceleration of the body.