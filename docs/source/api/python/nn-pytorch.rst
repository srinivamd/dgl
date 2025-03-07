.. _apinn-pytorch:

dgl.nn (PyTorch)
================

Conv Layers
----------------------------------------

.. autosummary::
    :toctree: ../../generated/
    :nosignatures:
    :template: classtemplate.rst

    ~dgl.nn.pytorch.conv.GraphConv
    ~dgl.nn.pytorch.conv.EdgeWeightNorm
    ~dgl.nn.pytorch.conv.RelGraphConv
    ~dgl.nn.pytorch.conv.TAGConv
    ~dgl.nn.pytorch.conv.GATConv
    ~dgl.nn.pytorch.conv.GATv2Conv
    ~dgl.nn.pytorch.conv.EGATConv
    ~dgl.nn.pytorch.conv.EdgeConv
    ~dgl.nn.pytorch.conv.SAGEConv
    ~dgl.nn.pytorch.conv.SGConv
    ~dgl.nn.pytorch.conv.APPNPConv
    ~dgl.nn.pytorch.conv.GINConv
    ~dgl.nn.pytorch.conv.GatedGraphConv
    ~dgl.nn.pytorch.conv.GMMConv
    ~dgl.nn.pytorch.conv.ChebConv
    ~dgl.nn.pytorch.conv.AGNNConv
    ~dgl.nn.pytorch.conv.NNConv
    ~dgl.nn.pytorch.conv.AtomicConv
    ~dgl.nn.pytorch.conv.CFConv
    ~dgl.nn.pytorch.conv.DotGatConv
    ~dgl.nn.pytorch.conv.TWIRLSConv
    ~dgl.nn.pytorch.conv.TWIRLSUnfoldingAndAttention
    ~dgl.nn.pytorch.conv.GCN2Conv

Dense Conv Layers
----------------------------------------

.. autosummary::
    :toctree: ../../generated/
    :nosignatures:
    :template: classtemplate.rst

    ~dgl.nn.pytorch.conv.DenseGraphConv
    ~dgl.nn.pytorch.conv.DenseSAGEConv
    ~dgl.nn.pytorch.conv.DenseChebConv

Global Pooling Layers
----------------------------------------

.. autosummary::
    :toctree: ../../generated/
    :nosignatures:
    :template: classtemplate.rst

    ~dgl.nn.pytorch.glob.SumPooling
    ~dgl.nn.pytorch.glob.AvgPooling
    ~dgl.nn.pytorch.glob.MaxPooling
    ~dgl.nn.pytorch.glob.SortPooling
    ~dgl.nn.pytorch.glob.WeightAndSum
    ~dgl.nn.pytorch.glob.GlobalAttentionPooling
    ~dgl.nn.pytorch.glob.Set2Set
    ~dgl.nn.pytorch.glob.SetTransformerEncoder
    ~dgl.nn.pytorch.glob.SetTransformerDecoder

Score Modules for Link Prediction and Knowledge Graph Completion
----------------------------------------

.. autosummary::
    :toctree: ../../generated/
    :nosignatures:
    :template: classtemplate.rst

    ~dgl.nn.pytorch.link.EdgePredictor
    ~dgl.nn.pytorch.link.TransE
    ~dgl.nn.pytorch.link.TransR

Heterogeneous Learning Modules
----------------------------------------

.. autosummary::
    :toctree: ../../generated/
    :nosignatures:
    :template: classtemplate.rst

    ~dgl.nn.pytorch.HeteroGraphConv
    ~dgl.nn.pytorch.HeteroLinear
    ~dgl.nn.pytorch.HeteroEmbedding
    ~dgl.nn.pytorch.TypedLinear

Utility Modules
----------------------------------------

.. autosummary::
    :toctree: ../../generated/
    :nosignatures:
    :template: classtemplate.rst

    ~dgl.nn.pytorch.utils.Sequential
    ~dgl.nn.pytorch.utils.WeightBasis
    ~dgl.nn.pytorch.factory.KNNGraph
    ~dgl.nn.pytorch.factory.SegmentedKNNGraph
    ~dgl.nn.pytorch.utils.JumpingKnowledge
    ~dgl.nn.pytorch.sparse_emb.NodeEmbedding
    ~dgl.nn.pytorch.explain.GNNExplainer
