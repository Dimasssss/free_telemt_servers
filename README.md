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

# Server Metrics 2026-03-19 05:58:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 29387.1 (8h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 442546
telemt_connections_bad_total 42945
telemt_connections_current 1254
telemt_connections_me_current 1254
telemt_handshake_timeouts_total 21785
telemt_upstream_connect_attempt_total 5700
telemt_upstream_connect_success_total 5601
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 5700
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2735
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2863
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 4155
telemt_me_reconnect_success_total 4134
telemt_me_reader_eof_total 4352
telemt_me_idle_close_by_peer_total 4351
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 115905
telemt_me_route_drop_channel_closed_total 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 328538
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2131
telemt_desync_full_logged_total 605
telemt_desync_suppressed_total 1526
telemt_desync_frames_bucket_total{bucket="1_2"} 751
telemt_desync_frames_bucket_total{bucket="3_10"} 840
telemt_desync_frames_bucket_total{bucket="gt_10"} 540
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4172
telemt_me_writer_restored_same_endpoint_total 4117
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 325790
telemt_user_connections_current{user="hello"} 1254
telemt_user_octets_from_client{user="hello"} 4066822404 (3.79 GB)
telemt_user_octets_to_client{user="hello"} 112073250904 (104.38 GB)
telemt_user_unique_ips_current{user="hello"} 447
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 29392.0 (8h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 918216
telemt_connections_bad_total 54385
telemt_connections_current 3229
telemt_connections_me_current 3229
telemt_handshake_timeouts_total 26412
telemt_upstream_connect_attempt_total 5546
telemt_upstream_connect_success_total 5445
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 5546
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2769
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_reconnect_attempts_total 3986
telemt_me_reconnect_success_total 3962
telemt_me_reader_eof_total 4171
telemt_me_idle_close_by_peer_total 4171
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 283453
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 754569
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3072
telemt_desync_full_logged_total 1055
telemt_desync_suppressed_total 2017
telemt_desync_frames_bucket_total{bucket="1_2"} 570
telemt_desync_frames_bucket_total{bucket="3_10"} 1153
telemt_desync_frames_bucket_total{bucket="gt_10"} 1349
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 4031
telemt_me_writer_restored_same_endpoint_total 3942
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 754453
telemt_user_connections_current{user="hello"} 3229
telemt_user_octets_from_client{user="hello"} 17305443720 (16.12 GB)
telemt_user_octets_to_client{user="hello"} 332960776788 (310.09 GB)
telemt_user_unique_ips_current{user="hello"} 1194
telemt_user_unique_ips_recent_window{user="hello"} 442
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 29389.5 (8h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 777885
telemt_connections_bad_total 130640
telemt_connections_current 2652
telemt_connections_me_current 2652
telemt_handshake_timeouts_total 25867
telemt_upstream_connect_attempt_total 5325
telemt_upstream_connect_success_total 5325
telemt_upstream_connect_attempts_per_request{bucket="1"} 5325
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2720
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2598
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3865
telemt_me_reconnect_success_total 3848
telemt_me_reader_eof_total 4075
telemt_me_idle_close_by_peer_total 4075
telemt_me_route_drop_no_conn_total 236968
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 564907
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2914
telemt_desync_full_logged_total 953
telemt_desync_suppressed_total 1961
telemt_desync_frames_bucket_total{bucket="1_2"} 516
telemt_desync_frames_bucket_total{bucket="3_10"} 1027
telemt_desync_frames_bucket_total{bucket="gt_10"} 1371
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 3920
telemt_me_writer_restored_same_endpoint_total 3832
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 564715
telemt_user_connections_current{user="hello"} 2652
telemt_user_octets_from_client{user="hello"} 10891001360 (10.14 GB)
telemt_user_octets_to_client{user="hello"} 334394712188 (311.43 GB)
telemt_user_unique_ips_current{user="hello"} 939
telemt_user_unique_ips_recent_window{user="hello"} 372
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 29442.5 (8h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 859473
telemt_connections_bad_total 87513
telemt_connections_current 2379
telemt_connections_me_current 2379
telemt_handshake_timeouts_total 20664
telemt_upstream_connect_attempt_total 5199
telemt_upstream_connect_success_total 5199
telemt_upstream_connect_attempts_per_request{bucket="1"} 5199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2565
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 3743
telemt_me_reconnect_success_total 3721
telemt_me_reader_eof_total 3923
telemt_me_idle_close_by_peer_total 3922
telemt_me_route_drop_no_conn_total 252736
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 558581
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2006
telemt_desync_full_logged_total 729
telemt_desync_suppressed_total 1277
telemt_desync_frames_bucket_total{bucket="1_2"} 363
telemt_desync_frames_bucket_total{bucket="3_10"} 812
telemt_desync_frames_bucket_total{bucket="gt_10"} 831
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 3774
telemt_me_writer_restored_same_endpoint_total 3697
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 557503
telemt_user_connections_current{user="hello"} 2379
telemt_user_octets_from_client{user="hello"} 8293087268 (7.72 GB)
telemt_user_octets_to_client{user="hello"} 214829341472 (200.08 GB)
telemt_user_unique_ips_current{user="hello"} 849
telemt_user_unique_ips_recent_window{user="hello"} 371
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 29385.8 (8h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1022410
telemt_connections_bad_total 291113
telemt_connections_current 2715
telemt_connections_me_current 2715
telemt_handshake_timeouts_total 26840
telemt_upstream_connect_attempt_total 5237
telemt_upstream_connect_success_total 5206
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 5237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2577
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_reconnect_attempts_total 3754
telemt_me_reconnect_success_total 3731
telemt_me_reader_eof_total 3950
telemt_me_idle_close_by_peer_total 3950
telemt_me_route_drop_no_conn_total 245188
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 599465
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2917
telemt_desync_full_logged_total 998
telemt_desync_suppressed_total 1919
telemt_desync_frames_bucket_total{bucket="1_2"} 713
telemt_desync_frames_bucket_total{bucket="3_10"} 1245
telemt_desync_frames_bucket_total{bucket="gt_10"} 959
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 3772
telemt_me_writer_restored_same_endpoint_total 3707
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 599378
telemt_user_connections_current{user="hello"} 2715
telemt_user_octets_from_client{user="hello"} 15745660136 (14.66 GB)
telemt_user_octets_to_client{user="hello"} 325985808812 (303.60 GB)
telemt_user_unique_ips_current{user="hello"} 971
telemt_user_unique_ips_recent_window{user="hello"} 400
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 29397.4 (8h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 174033
telemt_connections_bad_total 11252
telemt_connections_current 623
telemt_connections_me_current 623
telemt_handshake_timeouts_total 1332
telemt_upstream_connect_attempt_total 8004
telemt_upstream_connect_success_total 7794
telemt_upstream_connect_fail_total 210
telemt_upstream_connect_attempts_per_request{bucket="1"} 8004
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3999
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 210
telemt_me_reconnect_attempts_total 10759
telemt_me_reconnect_success_total 6322
telemt_me_reader_eof_total 6698
telemt_me_idle_close_by_peer_total 6698
telemt_me_route_drop_no_conn_total 69182
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 151681
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 189
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 116
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 80
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 6483
telemt_me_refill_failed_total 138
telemt_me_writer_restored_same_endpoint_total 6292
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 151677
telemt_user_connections_current{user="hello"} 623
telemt_user_octets_from_client{user="hello"} 2578849884 (2.40 GB)
telemt_user_octets_to_client{user="hello"} 85630250176 (79.75 GB)
telemt_user_unique_ips_current{user="hello"} 251
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 29388.2 (8h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 618583
telemt_connections_bad_total 76947
telemt_connections_current 2485
telemt_connections_me_current 2485
telemt_handshake_timeouts_total 27261
telemt_upstream_connect_attempt_total 5972
telemt_upstream_connect_success_total 5972
telemt_upstream_connect_attempts_per_request{bucket="1"} 5972
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2804
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 4518
telemt_me_reconnect_success_total 4505
telemt_me_reader_eof_total 4758
telemt_me_idle_close_by_peer_total 4758
telemt_me_route_drop_no_conn_total 218899
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 495248
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2797
telemt_desync_full_logged_total 1001
telemt_desync_suppressed_total 1796
telemt_desync_frames_bucket_total{bucket="1_2"} 565
telemt_desync_frames_bucket_total{bucket="3_10"} 1070
telemt_desync_frames_bucket_total{bucket="gt_10"} 1162
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 4556
telemt_me_writer_restored_same_endpoint_total 4490
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 495060
telemt_user_connections_current{user="hello"} 2485
telemt_user_octets_from_client{user="hello"} 6424457392 (5.98 GB)
telemt_user_octets_to_client{user="hello"} 286660703356 (266.97 GB)
telemt_user_unique_ips_current{user="hello"} 822
telemt_user_unique_ips_recent_window{user="hello"} 318
```