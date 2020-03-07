# CIFAR_10_Advanced_Convolutions_1
In thus repository I have used dilated convolutions and depth wise separable convolutions  along with normal convolutions on CIFAR-10 dataset.


# I received accuracy above 80% in the 6th epoch using 798,304 parameters.


# Training logs with accuracies :-


  0%|          | 0/782 [00:00<?, ?it/s]Epoch: 1 Learning_Rate [0.1]
/content/Model_and_summary.py:100: UserWarning: Implicit dimension choice for log_softmax has been deprecated. Change the call to include dim=X as an argument.
  return F.log_softmax(x)
Loss=1.5244123935699463 Batch_id=781 Accuracy=39.78: 100%|██████████| 782/782 [00:39<00:00, 21.21it/s]
  0%|          | 0/782 [00:00<?, ?it/s]
Test set: Average loss: 1.3870, Accuracy: 4904/10000 (49.04%)

Epoch: 2 Learning_Rate [0.1]
Loss=1.5042799711227417 Batch_id=781 Accuracy=56.90: 100%|██████████| 782/782 [00:40<00:00, 19.47it/s]
  0%|          | 0/782 [00:00<?, ?it/s]
Test set: Average loss: 1.0682, Accuracy: 6192/10000 (61.92%)

Epoch: 3 Learning_Rate [0.1]
Loss=0.794559895992279 Batch_id=781 Accuracy=65.48: 100%|██████████| 782/782 [00:41<00:00, 18.66it/s]
  0%|          | 0/782 [00:00<?, ?it/s]
Test set: Average loss: 0.8335, Accuracy: 7070/10000 (70.70%)

Epoch: 4 Learning_Rate [0.1]
Loss=0.5160939693450928 Batch_id=781 Accuracy=70.10: 100%|██████████| 782/782 [00:41<00:00, 18.83it/s]
  0%|          | 0/782 [00:00<?, ?it/s]
Test set: Average loss: 0.7816, Accuracy: 7257/10000 (72.57%)

Epoch: 5 Learning_Rate [0.1]
Loss=1.559235692024231 Batch_id=781 Accuracy=73.31: 100%|██████████| 782/782 [00:41<00:00, 18.78it/s]
  0%|          | 0/782 [00:00<?, ?it/s]
Test set: Average loss: 0.8452, Accuracy: 7040/10000 (70.40%)

Epoch: 6 Learning_Rate [0.1]
Loss=0.35980018973350525 Batch_id=781 Accuracy=75.43: 100%|██████████| 782/782 [00:41<00:00, 18.94it/s]
  0%|          | 0/782 [00:00<?, ?it/s]
Test set: Average loss: 0.6518, Accuracy: 7751/10000 (77.51%)

Epoch: 7 Learning_Rate [0.0010000000000000002]
Loss=0.35470232367515564 Batch_id=781 Accuracy=79.12: 100%|██████████| 782/782 [00:41<00:00, 18.71it/s]
  0%|          | 0/782 [00:00<?, ?it/s]
Test set: Average loss: 0.5480, Accuracy: 8094/10000 (80.94%)

Epoch: 8 Learning_Rate [0.010000000000000002]
Loss=1.1377911567687988 Batch_id=781 Accuracy=80.02: 100%|██████████| 782/782 [00:41<00:00, 19.05it/s]
  0%|          | 0/782 [00:00<?, ?it/s]
Test set: Average loss: 0.5377, Accuracy: 8132/10000 (81.32%)

Epoch: 9 Learning_Rate [0.010000000000000002]
Loss=0.5031262636184692 Batch_id=781 Accuracy=80.69: 100%|██████████| 782/782 [00:41<00:00, 18.90it/s]
  0%|          | 0/782 [00:00<?, ?it/s]
Test set: Average loss: 0.5273, Accuracy: 8168/10000 (81.68%)

Epoch: 10 Learning_Rate [0.010000000000000002]
Loss=0.6950119733810425 Batch_id=781 Accuracy=80.95: 100%|██████████| 782/782 [00:41<00:00, 18.84it/s]
  0%|          | 0/782 [00:00<?, ?it/s]
Test set: Average loss: 0.5248, Accuracy: 8185/10000 (81.85%)

Epoch: 11 Learning_Rate [0.010000000000000002]
Loss=0.8112646341323853 Batch_id=781 Accuracy=81.31: 100%|██████████| 782/782 [00:41<00:00, 18.94it/s]
  0%|          | 0/782 [00:00<?, ?it/s]
Test set: Average loss: 0.5243, Accuracy: 8213/10000 (82.13%)

Epoch: 12 Learning_Rate [0.010000000000000002]
Loss=0.675116777420044 Batch_id=781 Accuracy=81.76: 100%|██████████| 782/782 [00:41<00:00, 18.90it/s]
  0%|          | 0/782 [00:00<?, ?it/s]
Test set: Average loss: 0.5169, Accuracy: 8205/10000 (82.05%)

Epoch: 13 Learning_Rate [0.00010000000000000003]
Loss=0.6900625228881836 Batch_id=781 Accuracy=82.05: 100%|██████████| 782/782 [00:41<00:00, 18.67it/s]
  0%|          | 0/782 [00:00<?, ?it/s]
Test set: Average loss: 0.5104, Accuracy: 8234/10000 (82.34%)

Epoch: 14 Learning_Rate [0.0010000000000000002]
Loss=0.9725351333618164 Batch_id=781 Accuracy=82.05: 100%|██████████| 782/782 [00:41<00:00, 18.71it/s]
  0%|          | 0/782 [00:00<?, ?it/s]
Test set: Average loss: 0.5108, Accuracy: 8238/10000 (82.38%)

Epoch: 15 Learning_Rate [0.0010000000000000002]
Loss=0.3305704593658447 Batch_id=781 Accuracy=82.53: 100%|██████████| 782/782 [00:41<00:00, 18.66it/s]
  0%|          | 0/782 [00:00<?, ?it/s]
Test set: Average loss: 0.5127, Accuracy: 8236/10000 (82.36%)

Epoch: 16 Learning_Rate [0.0010000000000000002]
Loss=0.7300622463226318 Batch_id=781 Accuracy=82.19: 100%|██████████| 782/782 [00:42<00:00, 18.59it/s]
  0%|          | 0/782 [00:00<?, ?it/s]
Test set: Average loss: 0.5125, Accuracy: 8236/10000 (82.36%)

Epoch: 17 Learning_Rate [0.0010000000000000002]
Loss=0.7198653221130371 Batch_id=781 Accuracy=82.44: 100%|██████████| 782/782 [00:41<00:00, 18.69it/s]
  0%|          | 0/782 [00:00<?, ?it/s]
Test set: Average loss: 0.5103, Accuracy: 8247/10000 (82.47%)

Epoch: 18 Learning_Rate [0.0010000000000000002]
Loss=0.4172874689102173 Batch_id=781 Accuracy=82.42: 100%|██████████| 782/782 [00:41<00:00, 18.68it/s]
  0%|          | 0/782 [00:00<?, ?it/s]
Test set: Average loss: 0.5114, Accuracy: 8235/10000 (82.35%)

Epoch: 19 Learning_Rate [1.0000000000000004e-05]
Loss=0.5886644721031189 Batch_id=781 Accuracy=82.44: 100%|██████████| 782/782 [00:41<00:00, 18.94it/s]
  0%|          | 0/782 [00:00<?, ?it/s]
Test set: Average loss: 0.5095, Accuracy: 8241/10000 (82.41%)

Epoch: 20 Learning_Rate [0.00010000000000000003]
Loss=0.45713821053504944 Batch_id=781 Accuracy=82.23: 100%|██████████| 782/782 [00:41<00:00, 18.96it/s]

Test set: Average loss: 0.5087, Accuracy: 8260/10000 (82.60%)
