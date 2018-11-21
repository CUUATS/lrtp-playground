---
title: Planning Process
date: 2018-09-18T13:50:42-06:00
draft: true
menu: main
weight: 40
---

<rpc-chart url="data.csv"
   height="100"
   width="300"
   type="bar"
   switch="true"
   y-label="Score"
   x-label="Year"
   chart-title="Multiple Types Chart">
   <rpc-scale
   grid-lines="false">
   </rpc-scale> <rpc-dataset type="bar"
   fill="false"
   point-radius="0"
   border-color="blue"
   data="15,15,15,15"
   label="Nation - 2010"><rpc-dataset type="line"
   fill="start"
   point-radius="0"
   border-color="red"
   data="60,60,60,60"
   label="Nation - 2015">
   </rpc-dataset> </rpc-chart>

   <rpc-chart url="databaseline.csv"
      height="100"
      width="300"
      type="line"
      fill="false"
      switch="true"
      y-label="Score"
      x-label="Year"
      chart-title="Multiple Types Chart">
      <rpc-scale
      grid-lines="false">
      </rpc-scale> <rpc-dataset type="bar"
      order="1"
      fill="origin"
      border-color="lime"
      data="45,45,10,45"
      label="UA 2010"><rpc-dataset type="bar"
      fill="origin"
      border-color="red"
      data="60,60,60,60"
      label="UA - 2015">
      </rpc-dataset> </rpc-chart>

<rpc-chart url="data.csv"
      height="100"
      width="300"
      type="bar"
      switch="true"
      y-label="Score"
      x-label="Year"
      chart-title="Multiple Types Chart">
      <rpc-scale
      grid-lines="false">
      </rpc-scale> <rpc-dataset type="line"
      fill="false"
      point-radius="0"
      border-color="blue"
      data="15,15,15,15"
      label="Nation - 2010"><rpc-dataset type="line"
      fill="start"
      point-radius="0"
      border-color="red"
      data="60,60,60,60"
      label="Nation - 2015">
      </rpc-dataset> </rpc-chart>

<rpc-chart url="data.csv"
      height="100"
      width="300"
      type="horizontalBar"
      switch="true"
      y-label="Score"
      x-label="Year"
      chart-title="Multiple Types Chart">
      <rpc-scale
      grid-lines="false">
      </rpc-scale> <rpc-dataset type="line"
      fill="origin"
      point-radius="0"
      border-color="blue"
      data="2010,1960,1960,1995"
      label="Nation - 2010"><rpc-dataset type="line"
      fill="start"
      point-radius="0"
      border-color="red"
      data="60,60,60,60"
      label="Nation - 2015">
      </rpc-dataset> </rpc-chart>
