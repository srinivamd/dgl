.. _apidata:

dgl.data
=========

.. currentmodule:: dgl.data
.. automodule:: dgl.data

Base Class
---------------------------------------

.. autosummary::
    :toctree: ../../generated/
    :nosignatures:
    :template: classtemplate.rst

    DGLDataset
    CSVDataset

Node Prediction Datasets
---------------------------------------

Datasets for node classification/regression tasks

.. autosummary::
    :toctree: ../../generated/
    :nosignatures:
    :template: classtemplate.rst

    SSTDataset
    KarateClubDataset
    CoraGraphDataset
    CiteseerGraphDataset
    PubmedGraphDataset
    CoraFullDataset
    AIFBDataset
    MUTAGDataset
    BGSDataset
    AMDataset
    AmazonCoBuyComputerDataset
    AmazonCoBuyPhotoDataset
    CoauthorCSDataset
    CoauthorPhysicsDataset
    PPIDataset
    RedditDataset
    SBMMixtureDataset
    FraudDataset
    FraudYelpDataset
    FraudAmazonDataset

Edge Prediction Datasets
---------------------------------------

Datasets for edge classification/regression and link prediction

.. autosummary::
    :toctree: ../../generated/
    :nosignatures:
    :template: classtemplate.rst

    FB15k237Dataset
    FB15kDataset
    WN18Dataset
    BitcoinOTCDataset
    ICEWS18Dataset
    GDELTDataset

Graph Prediction Datasets
---------------------------------------

Datasets for graph classification/regression tasks

.. autosummary::
    :toctree: ../../generated/
    :nosignatures:
    :template: classtemplate.rst

    QM7bDataset
    QM9Dataset
    QM9EdgeDataset
    MiniGCDataset
    TUDataset
    LegacyTUDataset
    GINDataset
    FakeNewsDataset
    AsNodePredDataset
    AsEdgePredDataset

Dataset adapters
-------------------

.. autosummary::
    :toctree: ../../generated/
    :nosignatures:
    :template: classtemplate.rst

    AsNodePredDataset
    AsLinkPredDataset

Utilities
-----------------

.. autosummary::
    :toctree: ../../generated/
    :nosignatures:
    :template: classtemplate.rst

    utils.get_download_dir
    utils.download
    utils.check_sha1
    utils.extract_archive
    utils.split_dataset
    utils.load_labels
    utils.save_info
    utils.load_info
    utils.add_nodepred_split
    utils.Subset
