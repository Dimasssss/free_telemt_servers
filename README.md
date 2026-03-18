# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-18 16:55:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 5388.5 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 168430
telemt_connections_bad_total 12679
telemt_handshake_timeouts_total 5371
telemt_upstream_connect_attempt_total 760
telemt_upstream_connect_success_total 760
telemt_upstream_connect_attempts_per_request{bucket="1"} 760
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 379
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 358
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 475
telemt_me_reconnect_success_total 473
telemt_me_reader_eof_total 477
telemt_me_idle_close_by_peer_total 477
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 87779
telemt_me_route_drop_channel_closed_total 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 138665
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 791
telemt_desync_full_logged_total 232
telemt_desync_suppressed_total 559
telemt_desync_frames_bucket_total{bucket="1_2"} 191
telemt_desync_frames_bucket_total{bucket="3_10"} 262
telemt_desync_frames_bucket_total{bucket="gt_10"} 338
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 489
telemt_me_writer_restored_same_endpoint_total 461
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 138602
telemt_user_connections_current{user="hello"} 1305
telemt_user_octets_from_client{user="hello"} 1932001032 (1.80 GB)
telemt_user_octets_to_client{user="hello"} 48786486320 (45.44 GB)
telemt_user_unique_ips_current{user="hello"} 484
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 10217.3 (2h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1042357
telemt_connections_bad_total 67069
telemt_connections_current 3608
telemt_connections_me_current 3608
telemt_handshake_timeouts_total 15920
telemt_upstream_connect_attempt_total 1879
telemt_upstream_connect_success_total 1869
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1023
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 834
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 1321
telemt_me_reconnect_success_total 1311
telemt_me_reader_eof_total 1262
telemt_me_idle_close_by_peer_total 1261
telemt_me_route_drop_no_conn_total 1013371
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 908078
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2562
telemt_desync_full_logged_total 821
telemt_desync_suppressed_total 1741
telemt_desync_frames_bucket_total{bucket="1_2"} 506
telemt_desync_frames_bucket_total{bucket="3_10"} 1032
telemt_desync_frames_bucket_total{bucket="gt_10"} 1024
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1243
telemt_me_writer_restored_same_endpoint_total 1309
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 907234
telemt_user_connections_current{user="hello"} 3608
telemt_user_octets_from_client{user="hello"} 11573164272 (10.78 GB)
telemt_user_octets_to_client{user="hello"} 264022441472 (245.89 GB)
telemt_user_unique_ips_current{user="hello"} 1151
telemt_user_unique_ips_recent_window{user="hello"} 470
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 10145.6 (2h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 707787
telemt_connections_bad_total 49072
telemt_connections_current 3140
telemt_connections_me_current 3140
telemt_handshake_timeouts_total 15368
telemt_upstream_connect_attempt_total 1443
telemt_upstream_connect_success_total 1436
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 754
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 670
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 887
telemt_me_reconnect_success_total 877
telemt_me_reader_eof_total 925
telemt_me_idle_close_by_peer_total 925
telemt_me_route_drop_no_conn_total 352708
telemt_me_route_drop_channel_closed_total 32
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 599384
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2440
telemt_desync_full_logged_total 704
telemt_desync_suppressed_total 1736
telemt_desync_frames_bucket_total{bucket="1_2"} 551
telemt_desync_frames_bucket_total{bucket="3_10"} 908
telemt_desync_frames_bucket_total{bucket="gt_10"} 981
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 909
telemt_me_writer_restored_same_endpoint_total 860
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 599078
telemt_user_connections_current{user="hello"} 3140
telemt_user_octets_from_client{user="hello"} 10974331328 (10.22 GB)
telemt_user_octets_to_client{user="hello"} 247557781812 (230.56 GB)
telemt_user_unique_ips_current{user="hello"} 1024
telemt_user_unique_ips_recent_window{user="hello"} 393
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 10859.9 (3h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1044908
telemt_connections_bad_total 24156
telemt_connections_current 2564
telemt_connections_me_current 2564
telemt_handshake_timeouts_total 13198
telemt_upstream_connect_attempt_total 1718
telemt_upstream_connect_success_total 1706
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1718
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 811
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1133
telemt_me_reconnect_success_total 1123
telemt_me_reader_eof_total 1133
telemt_me_idle_close_by_peer_total 1132
telemt_me_route_drop_no_conn_total 1744792
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 937527
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3480
telemt_desync_full_logged_total 867
telemt_desync_suppressed_total 2613
telemt_desync_frames_bucket_total{bucket="1_2"} 818
telemt_desync_frames_bucket_total{bucket="3_10"} 1596
telemt_desync_frames_bucket_total{bucket="gt_10"} 1066
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1115
telemt_me_writer_restored_same_endpoint_total 1112
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 937467
telemt_user_connections_current{user="hello"} 2564
telemt_user_octets_from_client{user="hello"} 8171494184 (7.61 GB)
telemt_user_octets_to_client{user="hello"} 164280262364 (153.00 GB)
telemt_user_unique_ips_current{user="hello"} 835
telemt_user_unique_ips_recent_window{user="hello"} 425
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 5374.8 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 426447
telemt_connections_bad_total 86700
telemt_handshake_timeouts_total 3930
telemt_upstream_connect_attempt_total 943
telemt_upstream_connect_success_total 916
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 943
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 511
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 399
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 1625
telemt_me_reconnect_success_total 625
telemt_me_reader_eof_total 647
telemt_me_idle_close_by_peer_total 647
telemt_me_route_drop_no_conn_total 180064
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 303934
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1097
telemt_desync_full_logged_total 385
telemt_desync_suppressed_total 712
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 344
telemt_desync_frames_bucket_total{bucket="gt_10"} 582
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 660
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 599
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 303533
telemt_user_connections_current{user="hello"} 3270
telemt_user_octets_from_client{user="hello"} 4533301012 (4.22 GB)
telemt_user_octets_to_client{user="hello"} 120350053184 (112.08 GB)
telemt_user_unique_ips_current{user="hello"} 1056
telemt_user_unique_ips_recent_window{user="hello"} 433
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 10312.4 (2h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190054
telemt_connections_bad_total 7643
telemt_connections_current 813
telemt_connections_me_current 813
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 1869
telemt_upstream_connect_attempt_total 5985
telemt_upstream_connect_success_total 5974
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 5985
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3270
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2661
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 331052
telemt_me_reconnect_success_total 1590
telemt_me_reader_eof_total 1551
telemt_me_idle_close_by_peer_total 1551
telemt_me_route_drop_no_conn_total 104820
telemt_me_route_drop_channel_closed_total 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 167379
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 359
telemt_desync_full_logged_total 130
telemt_desync_suppressed_total 229
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 147
telemt_desync_frames_bucket_total{bucket="gt_10"} 153
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1524
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 1579
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 171104
telemt_user_connections_current{user="hello"} 813
telemt_user_octets_from_client{user="hello"} 2572067309 (2.40 GB)
telemt_user_octets_to_client{user="hello"} 36837967845 (34.31 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 301
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 9379.2 (2h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 562210
telemt_connections_bad_total 23384
telemt_connections_current 2638
telemt_connections_me_current 2638
telemt_handshake_timeouts_total 10954
telemt_upstream_connect_attempt_total 1747
telemt_upstream_connect_success_total 1746
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 957
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 780
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 16741
telemt_me_reconnect_success_total 1230
telemt_me_reader_eof_total 1197
telemt_me_idle_close_by_peer_total 1197
telemt_me_route_drop_no_conn_total 359823
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 485311
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1649
telemt_desync_full_logged_total 580
telemt_desync_suppressed_total 1069
telemt_desync_frames_bucket_total{bucket="1_2"} 385
telemt_desync_frames_bucket_total{bucket="3_10"} 584
telemt_desync_frames_bucket_total{bucket="gt_10"} 680
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1188
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 1169
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 484399
telemt_user_connections_current{user="hello"} 2638
telemt_user_octets_from_client{user="hello"} 8604185212 (8.01 GB)
telemt_user_octets_to_client{user="hello"} 223402010056 (208.06 GB)
telemt_user_unique_ips_current{user="hello"} 867
telemt_user_unique_ips_recent_window{user="hello"} 368
```