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

# Server Metrics 2026-03-17 22:13:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 98894.1 (27h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1203369
telemt_connections_bad_total 8709
telemt_handshake_timeouts_total 31619
telemt_upstream_connect_attempt_total 22383
telemt_upstream_connect_success_total 21890
telemt_upstream_connect_fail_total 493
telemt_upstream_connect_attempts_per_request{bucket="1"} 22383
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10387
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 493
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 31797
telemt_me_reconnect_success_total 14665
telemt_me_reader_eof_total 15938
telemt_me_idle_close_by_peer_total 15937
telemt_me_route_drop_no_conn_total 536277
telemt_me_route_drop_channel_closed_total 155
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1104235
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7310
telemt_desync_full_logged_total 2113
telemt_desync_suppressed_total 5197
telemt_desync_frames_bucket_total{bucket="1_2"} 1955
telemt_desync_frames_bucket_total{bucket="3_10"} 2761
telemt_desync_frames_bucket_total{bucket="gt_10"} 2594
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 15417
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 14643
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 752
telemt_user_connections_total{user="hello"} 1098466
telemt_user_connections_current{user="hello"} 593
telemt_user_octets_from_client{user="hello"} 20069548583 (18.69 GB)
telemt_user_octets_to_client{user="hello"} 392652814175 (365.69 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 99145.5 (27h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1268824
telemt_connections_bad_total 60237
telemt_handshake_timeouts_total 44817
telemt_upstream_connect_attempt_total 457838
telemt_upstream_connect_success_total 456938
telemt_upstream_connect_fail_total 900
telemt_upstream_connect_attempts_per_request{bucket="1"} 457838
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382939
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30706
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 900
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 58121
telemt_me_reconnect_success_total 14965
telemt_me_reader_eof_total 16958
telemt_me_idle_close_by_peer_total 16958
telemt_me_route_drop_no_conn_total 326718
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 662073
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2967
telemt_desync_full_logged_total 959
telemt_desync_suppressed_total 2008
telemt_desync_frames_bucket_total{bucket="1_2"} 563
telemt_desync_frames_bucket_total{bucket="3_10"} 1214
telemt_desync_frames_bucket_total{bucket="gt_10"} 1190
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 16500
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 14949
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1535
telemt_user_connections_total{user="hello"} 1098503
telemt_user_connections_current{user="hello"} 931
telemt_user_octets_from_client{user="hello"} 15131762530 (14.09 GB)
telemt_user_octets_to_client{user="hello"} 370144651446 (344.72 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 317
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 98921.3 (27h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 727283
telemt_connections_bad_total 44774
telemt_handshake_timeouts_total 22879
telemt_upstream_connect_attempt_total 23444
telemt_upstream_connect_success_total 23306
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 23444
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10669
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12543
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 39007
telemt_me_reconnect_success_total 18329
telemt_me_reader_eof_total 19991
telemt_me_idle_close_by_peer_total 19984
telemt_me_route_drop_no_conn_total 303331
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 624796
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2049
telemt_desync_full_logged_total 635
telemt_desync_suppressed_total 1414
telemt_desync_frames_bucket_total{bucket="1_2"} 566
telemt_desync_frames_bucket_total{bucket="3_10"} 805
telemt_desync_frames_bucket_total{bucket="gt_10"} 678
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 19225
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 18317
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 896
telemt_user_connections_total{user="hello"} 623060
telemt_user_connections_current{user="hello"} 688
telemt_user_octets_from_client{user="hello"} 30871875432 (28.75 GB)
telemt_user_octets_to_client{user="hello"} 271441442456 (252.80 GB)
telemt_user_unique_ips_current{user="hello"} 249
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 98980.9 (27h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1224218
telemt_connections_bad_total 41826
telemt_handshake_timeouts_total 21563
telemt_upstream_connect_attempt_total 83076
telemt_upstream_connect_success_total 82645
telemt_upstream_connect_fail_total 431
telemt_upstream_connect_attempts_per_request{bucket="1"} 83076
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70005
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12266
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 345
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 431
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 34663
telemt_me_reconnect_success_total 14341
telemt_me_reader_eof_total 15812
telemt_me_idle_close_by_peer_total 15810
telemt_me_route_drop_no_conn_total 506523
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1000629
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3631
telemt_desync_full_logged_total 1184
telemt_desync_suppressed_total 2447
telemt_desync_frames_bucket_total{bucket="1_2"} 889
telemt_desync_frames_bucket_total{bucket="3_10"} 1519
telemt_desync_frames_bucket_total{bucket="gt_10"} 1223
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 15243
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 14332
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 902
telemt_user_connections_total{user="hello"} 1063127
telemt_user_connections_current{user="hello"} 768
telemt_user_octets_from_client{user="hello"} 16689972339 (15.54 GB)
telemt_user_octets_to_client{user="hello"} 465079958761 (433.14 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 258
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 98953.1 (27h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 780678
telemt_connections_bad_total 92681
telemt_handshake_timeouts_total 6408
telemt_upstream_connect_attempt_total 42025
telemt_upstream_connect_success_total 41458
telemt_upstream_connect_fail_total 567
telemt_upstream_connect_attempts_per_request{bucket="1"} 42025
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 399
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 567
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 54991
telemt_me_reconnect_success_total 20040
telemt_me_reader_eof_total 21849
telemt_me_idle_close_by_peer_total 21847
telemt_me_route_drop_no_conn_total 246839
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 624714
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2850
telemt_desync_full_logged_total 841
telemt_desync_suppressed_total 2009
telemt_desync_frames_bucket_total{bucket="1_2"} 910
telemt_desync_frames_bucket_total{bucket="3_10"} 1143
telemt_desync_frames_bucket_total{bucket="gt_10"} 797
telemt_pool_swap_total 48
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21470
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 20032
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1430
telemt_user_connections_total{user="hello"} 641324
telemt_user_connections_current{user="hello"} 759
telemt_user_octets_from_client{user="hello"} 12424021904 (11.57 GB)
telemt_user_octets_to_client{user="hello"} 317360956712 (295.57 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 268
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 99113.7 (27h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1015408
telemt_connections_bad_total 80775
telemt_handshake_timeouts_total 9489
telemt_upstream_connect_attempt_total 19577
telemt_upstream_connect_success_total 19464
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 19577
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9301
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10046
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 25771
telemt_me_reconnect_success_total 14493
telemt_me_reader_eof_total 15739
telemt_me_idle_close_by_peer_total 15737
telemt_me_route_drop_no_conn_total 690765
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 998702
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2081
telemt_desync_full_logged_total 724
telemt_desync_suppressed_total 1357
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 786
telemt_desync_frames_bucket_total{bucket="gt_10"} 834
telemt_pool_swap_total 85
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 15085
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 14479
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 592
telemt_user_connections_total{user="hello"} 861731
telemt_user_connections_current{user="hello"} 463
telemt_user_octets_from_client{user="hello"} 13355444008 (12.44 GB)
telemt_user_octets_to_client{user="hello"} 367128152840 (341.91 GB)
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 46881.0 (13h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 351319
telemt_connections_bad_total 44366
telemt_handshake_timeouts_total 10549
telemt_upstream_connect_attempt_total 18333
telemt_upstream_connect_success_total 18159
telemt_upstream_connect_fail_total 174
telemt_upstream_connect_attempts_per_request{bucket="1"} 18333
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9704
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8362
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 174
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 27235
telemt_me_reconnect_success_total 15641
telemt_me_reader_eof_total 16529
telemt_me_idle_close_by_peer_total 16529
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 86903
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 266652
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 899
telemt_desync_full_logged_total 271
telemt_desync_suppressed_total 628
telemt_desync_frames_bucket_total{bucket="1_2"} 209
telemt_desync_frames_bucket_total{bucket="3_10"} 358
telemt_desync_frames_bucket_total{bucket="gt_10"} 332
telemt_pool_swap_total 25
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 16185
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 15612
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 544
telemt_user_connections_total{user="hello"} 266592
telemt_user_connections_current{user="hello"} 452
telemt_user_octets_from_client{user="hello"} 21255462409 (19.80 GB)
telemt_user_octets_to_client{user="hello"} 220528290010 (205.38 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 43
```