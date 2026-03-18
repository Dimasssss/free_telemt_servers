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

# Server Metrics 2026-03-18 05:00:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 123338.9 (34h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1419305
telemt_connections_bad_total 10563
telemt_handshake_timeouts_total 34627
telemt_upstream_connect_attempt_total 26985
telemt_upstream_connect_success_total 26471
telemt_upstream_connect_fail_total 514
telemt_upstream_connect_attempts_per_request{bucket="1"} 26985
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13566
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12697
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 514
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 266
telemt_me_reconnect_attempts_total 35202
telemt_me_reconnect_success_total 18054
telemt_me_reader_eof_total 19582
telemt_me_idle_close_by_peer_total 19581
telemt_me_route_drop_no_conn_total 600838
telemt_me_route_drop_channel_closed_total 165
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1299067
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8030
telemt_desync_full_logged_total 2403
telemt_desync_suppressed_total 5627
telemt_desync_frames_bucket_total{bucket="1_2"} 2111
telemt_desync_frames_bucket_total{bucket="3_10"} 3077
telemt_desync_frames_bucket_total{bucket="gt_10"} 2842
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 18858
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 18032
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 804
telemt_user_connections_total{user="hello"} 1293300
telemt_user_connections_current{user="hello"} 944
telemt_user_octets_from_client{user="hello"} 29794678587 (27.75 GB)
telemt_user_octets_to_client{user="hello"} 457339204807 (425.93 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 347
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 123590.2 (34h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1536375
telemt_connections_bad_total 74191
telemt_handshake_timeouts_total 50926
telemt_upstream_connect_attempt_total 470467
telemt_upstream_connect_success_total 468842
telemt_upstream_connect_fail_total 1625
telemt_upstream_connect_attempts_per_request{bucket="1"} 470467
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 390925
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34552
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43363
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1625
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 126488
telemt_me_reconnect_success_total 19760
telemt_me_reader_eof_total 22039
telemt_me_idle_close_by_peer_total 22026
telemt_me_route_drop_no_conn_total 400794
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 894677
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4005
telemt_desync_full_logged_total 1397
telemt_desync_suppressed_total 2608
telemt_desync_frames_bucket_total{bucket="1_2"} 787
telemt_desync_frames_bucket_total{bucket="3_10"} 1635
telemt_desync_frames_bucket_total{bucket="gt_10"} 1583
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 21383
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 19742
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1623
telemt_user_connections_total{user="hello"} 1336991
telemt_user_connections_current{user="hello"} 1415
telemt_user_octets_from_client{user="hello"} 18174020837 (16.93 GB)
telemt_user_octets_to_client{user="hello"} 500486024554 (466.11 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 499
telemt_user_unique_ips_recent_window{user="hello"} 192
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 123366.3 (34h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 974373
telemt_connections_bad_total 69091
telemt_handshake_timeouts_total 27815
telemt_upstream_connect_attempt_total 28363
telemt_upstream_connect_success_total 28202
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 28363
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12927
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15173
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 42715
telemt_me_reconnect_success_total 22015
telemt_me_reader_eof_total 23928
telemt_me_idle_close_by_peer_total 23921
telemt_me_route_drop_no_conn_total 364093
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 800583
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2598
telemt_desync_full_logged_total 858
telemt_desync_suppressed_total 1740
telemt_desync_frames_bucket_total{bucket="1_2"} 724
telemt_desync_frames_bucket_total{bucket="3_10"} 1001
telemt_desync_frames_bucket_total{bucket="gt_10"} 873
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 22955
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 22003
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 940
telemt_user_connections_total{user="hello"} 798690
telemt_user_connections_current{user="hello"} 1054
telemt_user_octets_from_client{user="hello"} 45284252452 (42.17 GB)
telemt_user_octets_to_client{user="hello"} 374296090084 (348.59 GB)
telemt_user_unique_ips_current{user="hello"} 341
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 123425.5 (34h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1428613
telemt_connections_bad_total 70300
telemt_handshake_timeouts_total 24537
telemt_upstream_connect_attempt_total 91385
telemt_upstream_connect_success_total 88944
telemt_upstream_connect_fail_total 2441
telemt_upstream_connect_attempts_per_request{bucket="1"} 91385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14854
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 377
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2441
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 38431
telemt_me_reconnect_success_total 18019
telemt_me_reader_eof_total 19776
telemt_me_idle_close_by_peer_total 19773
telemt_me_route_drop_no_conn_total 578008
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1163342
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4383
telemt_desync_full_logged_total 1442
telemt_desync_suppressed_total 2941
telemt_desync_frames_bucket_total{bucket="1_2"} 1064
telemt_desync_frames_bucket_total{bucket="3_10"} 1846
telemt_desync_frames_bucket_total{bucket="gt_10"} 1473
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 18989
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 17999
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 970
telemt_user_connections_total{user="hello"} 1226645
telemt_user_connections_current{user="hello"} 1231
telemt_user_octets_from_client{user="hello"} 19187910242 (17.87 GB)
telemt_user_octets_to_client{user="hello"} 596231719474 (555.28 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 389
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 123397.4 (34h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 992423
telemt_connections_bad_total 102901
telemt_handshake_timeouts_total 9479
telemt_upstream_connect_attempt_total 48353
telemt_upstream_connect_success_total 47685
telemt_upstream_connect_fail_total 668
telemt_upstream_connect_attempts_per_request{bucket="1"} 48353
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29478
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17786
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 421
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 668
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 60020
telemt_me_reconnect_success_total 25053
telemt_me_reader_eof_total 27100
telemt_me_idle_close_by_peer_total 27097
telemt_me_route_drop_no_conn_total 317640
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 810005
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3617
telemt_desync_full_logged_total 1100
telemt_desync_suppressed_total 2517
telemt_desync_frames_bucket_total{bucket="1_2"} 1071
telemt_desync_frames_bucket_total{bucket="3_10"} 1406
telemt_desync_frames_bucket_total{bucket="gt_10"} 1140
telemt_pool_swap_total 64
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 26533
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 25045
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1480
telemt_user_connections_total{user="hello"} 826483
telemt_user_connections_current{user="hello"} 1146
telemt_user_octets_from_client{user="hello"} 15772571860 (14.69 GB)
telemt_user_octets_to_client{user="hello"} 419453406644 (390.65 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 412
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 123558.9 (34h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1188125
telemt_connections_bad_total 127263
telemt_handshake_timeouts_total 10410
telemt_upstream_connect_attempt_total 24629
telemt_upstream_connect_success_total 24484
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 24628
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11754
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12611
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 29628
telemt_me_reconnect_success_total 18333
telemt_me_reader_eof_total 19873
telemt_me_idle_close_by_peer_total 19871
telemt_me_route_drop_no_conn_total 817505
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1168490
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2210
telemt_desync_full_logged_total 774
telemt_desync_suppressed_total 1436
telemt_desync_frames_bucket_total{bucket="1_2"} 484
telemt_desync_frames_bucket_total{bucket="3_10"} 842
telemt_desync_frames_bucket_total{bucket="gt_10"} 884
telemt_pool_swap_total 112
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 18971
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 18319
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 638
telemt_user_connections_total{user="hello"} 977176
telemt_user_connections_current{user="hello"} 662
telemt_user_octets_from_client{user="hello"} 15524791328 (14.46 GB)
telemt_user_octets_to_client{user="hello"} 430474871384 (400.91 GB)
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 71325.7 (19h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 528216
telemt_connections_bad_total 53556
telemt_handshake_timeouts_total 13063
telemt_upstream_connect_attempt_total 25228
telemt_upstream_connect_success_total 24967
telemt_upstream_connect_fail_total 261
telemt_upstream_connect_attempts_per_request{bucket="1"} 25228
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13353
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 261
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 32868
telemt_me_reconnect_success_total 21256
telemt_me_reader_eof_total 22466
telemt_me_idle_close_by_peer_total 22466
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 128723
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 379628
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1657
telemt_desync_full_logged_total 545
telemt_desync_suppressed_total 1112
telemt_desync_frames_bucket_total{bucket="1_2"} 277
telemt_desync_frames_bucket_total{bucket="3_10"} 742
telemt_desync_frames_bucket_total{bucket="gt_10"} 638
telemt_pool_swap_total 49
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21844
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 21213
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 588
telemt_user_connections_total{user="hello"} 379383
telemt_user_connections_current{user="hello"} 911
telemt_user_octets_from_client{user="hello"} 24230909149 (22.57 GB)
telemt_user_octets_to_client{user="hello"} 302860744574 (282.06 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 288
telemt_user_unique_ips_recent_window{user="hello"} 128
```