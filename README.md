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

# Server Metrics 2026-03-18 10:57:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 8186.9 (2h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 296925
telemt_connections_bad_total 1876
telemt_handshake_timeouts_total 6982
telemt_upstream_connect_attempt_total 64619
telemt_upstream_connect_success_total 63691
telemt_upstream_connect_fail_total 928
telemt_upstream_connect_attempts_per_request{bucket="1"} 64619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3326
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 928
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 507926
telemt_me_reconnect_success_total 1283
telemt_me_reader_eof_total 1246
telemt_me_idle_close_by_peer_total 1244
telemt_me_route_drop_no_conn_total 171778
telemt_me_route_drop_channel_closed_total 56
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 202521
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 904
telemt_desync_full_logged_total 288
telemt_desync_suppressed_total 616
telemt_desync_frames_bucket_total{bucket="1_2"} 266
telemt_desync_frames_bucket_total{bucket="3_10"} 331
telemt_desync_frames_bucket_total{bucket="gt_10"} 307
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1278
telemt_me_refill_failed_total 16516
telemt_me_writer_restored_same_endpoint_total 1178
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_user_connections_total{user="hello"} 260991
telemt_user_connections_current{user="hello"} 1472
telemt_user_octets_from_client{user="hello"} 3352645600 (3.12 GB)
telemt_user_octets_to_client{user="hello"} 66308691833 (61.75 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 518
telemt_user_unique_ips_recent_window{user="hello"} 255
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 8217.5 (2h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 882338
telemt_connections_bad_total 77500
telemt_handshake_timeouts_total 20031
telemt_upstream_connect_attempt_total 1432
telemt_upstream_connect_success_total 1419
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1431
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 604
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 959
telemt_me_reconnect_success_total 929
telemt_me_reader_eof_total 911
telemt_me_idle_close_by_peer_total 911
telemt_me_route_drop_no_conn_total 883582
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 743681
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2614
telemt_desync_full_logged_total 738
telemt_desync_suppressed_total 1876
telemt_desync_frames_bucket_total{bucket="1_2"} 536
telemt_desync_frames_bucket_total{bucket="3_10"} 1037
telemt_desync_frames_bucket_total{bucket="gt_10"} 1041
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 922
telemt_me_writer_restored_same_endpoint_total 928
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 742924
telemt_user_connections_current{user="hello"} 3670
telemt_user_octets_from_client{user="hello"} 11312011680 (10.54 GB)
telemt_user_octets_to_client{user="hello"} 204095233152 (190.08 GB)
telemt_user_unique_ips_current{user="hello"} 1111
telemt_user_unique_ips_recent_window{user="hello"} 512
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 8132.5 (2h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 561854
telemt_connections_bad_total 40339
telemt_handshake_timeouts_total 13942
telemt_upstream_connect_attempt_total 9827
telemt_upstream_connect_success_total 9827
telemt_upstream_connect_attempts_per_request{bucket="1"} 9827
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7817
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2000
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 606859
telemt_me_reconnect_success_total 1183
telemt_me_reader_eof_total 1164
telemt_me_idle_close_by_peer_total 1163
telemt_me_route_drop_no_conn_total 276941
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 423926
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1071
telemt_desync_full_logged_total 360
telemt_desync_suppressed_total 711
telemt_desync_frames_bucket_total{bucket="1_2"} 267
telemt_desync_frames_bucket_total{bucket="3_10"} 408
telemt_desync_frames_bucket_total{bucket="gt_10"} 396
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1181
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 1148
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_user_connections_total{user="hello"} 431779
telemt_user_connections_current{user="hello"} 3001
telemt_user_octets_from_client{user="hello"} 4677336131 (4.36 GB)
telemt_user_octets_to_client{user="hello"} 160330438072 (149.32 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 888
telemt_user_unique_ips_recent_window{user="hello"} 425
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 8162.8 (2h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1011450
telemt_connections_bad_total 12403
telemt_handshake_timeouts_total 119342
telemt_upstream_connect_attempt_total 11937
telemt_upstream_connect_success_total 11803
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 11937
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1156
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2818881
telemt_me_reconnect_success_total 1078
telemt_me_reader_eof_total 1286
telemt_me_idle_close_by_peer_total 1286
telemt_me_route_drop_no_conn_total 1759386
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 787906
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 8840
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_writer_pick_blocking_fallback_total 8840
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1367
telemt_desync_full_logged_total 410
telemt_desync_suppressed_total 957
telemt_desync_frames_bucket_total{bucket="1_2"} 341
telemt_desync_frames_bucket_total{bucket="3_10"} 552
telemt_desync_frames_bucket_total{bucket="gt_10"} 474
telemt_me_writer_removed_unexpected_total 1323
telemt_me_refill_failed_total 99794
telemt_me_writer_restored_same_endpoint_total 983
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 245
telemt_user_connections_total{user="hello"} 806806
telemt_user_connections_current{user="hello"} 2657
telemt_user_octets_from_client{user="hello"} 5699289046 (5.31 GB)
telemt_user_octets_to_client{user="hello"} 115660015989 (107.72 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 818
telemt_user_unique_ips_recent_window{user="hello"} 408
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 8057.8 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 555922
telemt_connections_bad_total 16279
telemt_handshake_timeouts_total 8435
telemt_upstream_connect_attempt_total 10952
telemt_upstream_connect_success_total 10951
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10952
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9715
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1017
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 219
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2982976
telemt_me_reconnect_success_total 1024
telemt_me_reader_eof_total 991
telemt_me_idle_close_by_peer_total 991
telemt_me_route_drop_no_conn_total 234795
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 468340
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1736
telemt_desync_full_logged_total 584
telemt_desync_suppressed_total 1152
telemt_desync_frames_bucket_total{bucket="1_2"} 267
telemt_desync_frames_bucket_total{bucket="3_10"} 676
telemt_desync_frames_bucket_total{bucket="gt_10"} 793
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 983
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 909
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 476682
telemt_user_connections_current{user="hello"} 3611
telemt_user_octets_from_client{user="hello"} 7575316469 (7.06 GB)
telemt_user_octets_to_client{user="hello"} 194060118385 (180.73 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 1058
telemt_user_unique_ips_recent_window{user="hello"} 499
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 7942.3 (2h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 171490
telemt_connections_bad_total 18707
telemt_handshake_timeouts_total 1140
telemt_upstream_connect_attempt_total 1434
telemt_upstream_connect_success_total 1434
telemt_upstream_connect_attempts_per_request{bucket="1"} 1434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 773
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 661
telemt_me_reconnect_attempts_total 1002
telemt_me_reconnect_success_total 992
telemt_me_reader_eof_total 1004
telemt_me_idle_close_by_peer_total 1003
telemt_me_route_drop_no_conn_total 82287
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 145129
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 371
telemt_desync_full_logged_total 128
telemt_desync_suppressed_total 243
telemt_desync_frames_bucket_total{bucket="1_2"} 71
telemt_desync_frames_bucket_total{bucket="3_10"} 134
telemt_desync_frames_bucket_total{bucket="gt_10"} 166
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 995
telemt_me_writer_restored_same_endpoint_total 984
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 137885
telemt_user_connections_current{user="hello"} 932
telemt_user_octets_from_client{user="hello"} 2059185196 (1.92 GB)
telemt_user_octets_to_client{user="hello"} 34013853588 (31.68 GB)
telemt_user_unique_ips_current{user="hello"} 339
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 8013.5 (2h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 406591
telemt_connections_bad_total 21702
telemt_handshake_timeouts_total 9248
telemt_upstream_connect_attempt_total 1419
telemt_upstream_connect_success_total 1400
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 1419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 786
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 606
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 976
telemt_me_reconnect_success_total 957
telemt_me_reader_eof_total 959
telemt_me_idle_close_by_peer_total 959
telemt_me_route_drop_no_conn_total 206743
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 348825
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1314
telemt_desync_full_logged_total 454
telemt_desync_suppressed_total 860
telemt_desync_frames_bucket_total{bucket="1_2"} 253
telemt_desync_frames_bucket_total{bucket="3_10"} 475
telemt_desync_frames_bucket_total{bucket="gt_10"} 586
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 955
telemt_me_writer_restored_same_endpoint_total 947
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_user_connections_total{user="hello"} 348614
telemt_user_connections_current{user="hello"} 2795
telemt_user_octets_from_client{user="hello"} 5937648496 (5.53 GB)
telemt_user_octets_to_client{user="hello"} 177487032244 (165.30 GB)
telemt_user_unique_ips_current{user="hello"} 803
telemt_user_unique_ips_recent_window{user="hello"} 389
```