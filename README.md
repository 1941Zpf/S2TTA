<div align="center">
  <h1>A Stable Self-evolving Target Template Helps Test-Time Adaptation in Multimodal Object Tracking</h1>
</div>

## Abstract
Abstract

RGB-X multimodal trackers have recently achieved remarkable progress by exploiting complementary information from heterogeneous modalities. However, existing methods often overlook performance degradation caused by distribution shifts between training and testing environments. Although recent test-time adaptation approaches have been explored for multimodal tracking, their adaptation objectives are often derived from test-time confidence estimates or source-domain statistics, which may become less reliable under significant distribution shifts.
To address these challenges, we propose S²TTA, a stable self-evolving target template-guided test-time adaptation framework. S²TTA constructs a target-specific template prior and performs uncertainty-aware prior evolution to provide reliable test-time optimization objectives. Through a hierarchical adaptation space and discrepancy-guided space selection, S²TTA adaptively selects appropriate adaptation spaces according to the distribution shifts of different modalities.
Extensive experiments demonstrate that S²TTA consistently achieves superior performance and significantly improves model robustness and generalization ability.
