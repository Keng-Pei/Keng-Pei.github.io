---
title: Binary Tree Traversal
date: 2024-02-05 16:07:00 +0800 
categories: [leetcode,binarytree]
tags: [leetcode,binarytree,c]     # TAG names should always be lowercase
---
有分為四種traversal順序:
1.  preorder traversal  :中->左->右     4->2->1->3->5
2.  inorder traversal   :左->中->右     1->2->3->4->5
3.  postorder traversal :左->右->中     1->3->2->5->4
4.  level-order traversal   :由上到下，由左至右，一層一層搜索       4->2->5->1->3

以下圖為例:

![image](\assets\image\binarytree)
