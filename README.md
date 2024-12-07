# HuggingFaceModelDeployment_AWS_Sagemaker

## Table of Contents
 * [Introduction](#introduction)
 * [Setup of AWS Sagemaker Studio](#setup-of-aws-sagemaker-studio)
 * [Run and Deploy the model](#run-and-deploy-the-model)
 * [Test Inference](#test--inference)

## Introduction
  This project is about using a huggingface model on the task of Question Answering and Deploying it on AWS Sagemaker Studio. First we create a bucket in AWS S3 where the model is stored. Then we configure for loading the model from the hub. Create IAM role with permissions to create an endpoint. Then the model is deployed to Sagemaker Inference.

## Setup of AWS Sagemaker Studio
