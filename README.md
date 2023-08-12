The size for the file featured within this Kaggle dataset is shown below — along with a list of attributes, and their description summaries:

    thyroidDF.csv - 9172 observations x 31 attributes

    age - age of the patient (int)
    sex - sex patient identifies (str)
    on_thyroxine - whether patient is on thyroxine (bool)
    query on thyroxine - *whether patient is on thyroxine (bool)
    on antithyroid meds - whether patient is on antithyroid meds (bool)
    sick - whether patient is sick (bool)
    pregnant - whether patient is pregnant (bool)
    thyroid_surgery - whether patient has undergone thyroid surgery (bool)
    I131_treatment - whether patient is undergoing I131 treatment (bool)
    query_hypothyroid - whether patient believes they have hypothyroid (bool)
    query_hyperthyroid - whether patient believes they have hyperthyroid (bool)
    lithium - whether patient * lithium (bool)
    goitre - whether patient has goitre (bool)
    tumor - whether patient has tumor (bool)
    hypopituitary - whether patient * hyperpituitary gland (float)
    psych - whether patient * psych (bool)
    TSH_measured - whether TSH was measured in the blood (bool)
    TSH - TSH level in blood from lab work (float)
    T3_measured - whether T3 was measured in the blood (bool)
    T3 - T3 level in blood from lab work (float)
    TT4_measured - whether TT4 was measured in the blood (bool)
    TT4 - TT4 level in blood from lab work (float)
    T4U_measured - whether T4U was measured in the blood (bool)
    T4U - T4U level in blood from lab work (float)
    FTI_measured - whether FTI was measured in the blood (bool)
    FTI - FTI level in blood from lab work (float)
    TBG_measured - whether TBG was measured in the blood (bool)
    TBG - TBG level in blood from lab work (float)
    referral_source - (str)
    target - hyperthyroidism medical diagnosis (str)
    patient_id - unique id of the patient (str)

Target Metadata

    The diagnosis consists of a string of letters indicating diagnosed conditions.
    A diagnosis "-" indicates no condition requiring comment.  A diagnosis of the
    form "X|Y" is interpreted as "consistent with X, but more likely Y".  The
    conditions are divided into groups where each group corresponds to a class of
    comments.

    Letter  Diagnosis
    ------  ---------

    hyperthyroid conditions:

    A   hyperthyroid
    B   T3 toxic
    C   toxic goitre
    D   secondary toxic

    hypothyroid conditions:

    E   hypothyroid
    F   primary hypothyroid
    G   compensated hypothyroid
    H   secondary hypothyroid

    binding protein:

    I   increased binding protein
    J   decreased binding protein

    general health:

    K   concurrent non-thyroidal illness

    replacement therapy:

    L   consistent with replacement therapy
    M   underreplaced
    N   overreplaced

    antithyroid treatment:

    O   antithyroid drugs
    P   I131 treatment
    Q   surgery

    miscellaneous:

    R   discordant assay results
    S   elevated TBG
    T   elevated thyroid hormones

Source

Thyroid Data - https://archive.ics.uci.edu/ml/datasets/thyroid+disease