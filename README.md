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

# Server Metrics 2026-03-17 14:44:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 71952.1 (19h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 770922
telemt_connections_bad_total 5809
telemt_handshake_timeouts_total 22905
telemt_upstream_connect_attempt_total 17371
telemt_upstream_connect_success_total 16913
telemt_upstream_connect_fail_total 458
telemt_upstream_connect_attempts_per_request{bucket="1"} 17371
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7889
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 458
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 22967
telemt_me_reconnect_success_total 11023
telemt_me_reader_eof_total 11949
telemt_me_idle_close_by_peer_total 11948
telemt_me_route_drop_no_conn_total 306491
telemt_me_route_drop_channel_closed_total 76
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 698654
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4840
telemt_desync_full_logged_total 1359
telemt_desync_suppressed_total 3481
telemt_desync_frames_bucket_total{bucket="1_2"} 1371
telemt_desync_frames_bucket_total{bucket="3_10"} 1950
telemt_desync_frames_bucket_total{bucket="gt_10"} 1519
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 11549
telemt_me_refill_failed_total 368
telemt_me_writer_restored_same_endpoint_total 11001
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 526
telemt_user_connections_total{user="hello"} 700517
telemt_user_connections_current{user="hello"} 1014
telemt_user_octets_from_client{user="hello"} 11662283283 (10.86 GB)
telemt_user_octets_to_client{user="hello"} 233388752339 (217.36 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 339
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 72203.4 (20h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 490789
telemt_connections_bad_total 31606
telemt_handshake_timeouts_total 24770
telemt_upstream_connect_attempt_total 64977
telemt_upstream_connect_success_total 64490
telemt_upstream_connect_fail_total 487
telemt_upstream_connect_attempts_per_request{bucket="1"} 64977
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11355
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4926
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 487
telemt_me_keepalive_timeout_total 326
telemt_me_reconnect_attempts_total 35485
telemt_me_reconnect_success_total 13399
telemt_me_reader_eof_total 14649
telemt_me_idle_close_by_peer_total 14649
telemt_me_route_drop_no_conn_total 189596
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 363707
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1458
telemt_desync_full_logged_total 457
telemt_desync_suppressed_total 1001
telemt_desync_frames_bucket_total{bucket="1_2"} 327
telemt_desync_frames_bucket_total{bucket="3_10"} 638
telemt_desync_frames_bucket_total{bucket="gt_10"} 493
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14252
telemt_me_refill_failed_total 686
telemt_me_writer_restored_same_endpoint_total 13383
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 853
telemt_user_connections_total{user="hello"} 411062
telemt_user_connections_current{user="hello"} 603
telemt_user_octets_from_client{user="hello"} 4443225824 (4.14 GB)
telemt_user_octets_to_client{user="hello"} 124337864279 (115.80 GB)
telemt_user_msgs_from_client{user="hello"} 662220
telemt_user_msgs_to_client{user="hello"} 2151373
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 71979.6 (19h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 255425
telemt_connections_bad_total 7816
telemt_handshake_timeouts_total 17124
telemt_upstream_connect_attempt_total 18944
telemt_upstream_connect_success_total 18849
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 18944
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10321
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 24907
telemt_me_reconnect_success_total 15215
telemt_me_reader_eof_total 16385
telemt_me_idle_close_by_peer_total 16382
telemt_me_route_drop_no_conn_total 115541
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 217186
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 790
telemt_desync_full_logged_total 227
telemt_desync_suppressed_total 563
telemt_desync_frames_bucket_total{bucket="1_2"} 288
telemt_desync_frames_bucket_total{bucket="3_10"} 356
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 15726
telemt_me_refill_failed_total 300
telemt_me_writer_restored_same_endpoint_total 15204
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 511
telemt_user_connections_total{user="hello"} 217052
telemt_user_connections_current{user="hello"} 324
telemt_user_octets_from_client{user="hello"} 17306821532 (16.12 GB)
telemt_user_octets_to_client{user="hello"} 54432587628 (50.69 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 72038.8 (20h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 589464
telemt_connections_bad_total 8342
telemt_handshake_timeouts_total 13275
telemt_upstream_connect_attempt_total 16690
telemt_upstream_connect_success_total 16532
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 16690
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8127
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 23941
telemt_me_reconnect_success_total 11878
telemt_me_reader_eof_total 12908
telemt_me_idle_close_by_peer_total 12907
telemt_me_route_drop_no_conn_total 218116
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 505781
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1735
telemt_desync_full_logged_total 593
telemt_desync_suppressed_total 1142
telemt_desync_frames_bucket_total{bucket="1_2"} 442
telemt_desync_frames_bucket_total{bucket="3_10"} 772
telemt_desync_frames_bucket_total{bucket="gt_10"} 521
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12462
telemt_me_refill_failed_total 372
telemt_me_writer_restored_same_endpoint_total 11869
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 584
telemt_user_connections_total{user="hello"} 506609
telemt_user_connections_current{user="hello"} 658
telemt_user_octets_from_client{user="hello"} 6346116494 (5.91 GB)
telemt_user_octets_to_client{user="hello"} 162350626375 (151.20 GB)
telemt_user_msgs_from_client{user="hello"} 4070
telemt_user_msgs_to_client{user="hello"} 5224
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 72010.7 (20h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 280885
telemt_connections_bad_total 57035
telemt_handshake_timeouts_total 3565
telemt_upstream_connect_attempt_total 20994
telemt_upstream_connect_success_total 20533
telemt_upstream_connect_fail_total 461
telemt_upstream_connect_attempts_per_request{bucket="1"} 20994
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9245
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11002
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 286
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 461
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 38410
telemt_me_reconnect_success_total 16532
telemt_me_reader_eof_total 17803
telemt_me_idle_close_by_peer_total 17801
telemt_me_route_drop_no_conn_total 79050
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 208465
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1120
telemt_desync_full_logged_total 238
telemt_desync_suppressed_total 882
telemt_desync_frames_bucket_total{bucket="1_2"} 560
telemt_desync_frames_bucket_total{bucket="3_10"} 431
telemt_desync_frames_bucket_total{bucket="gt_10"} 129
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 17491
telemt_me_refill_failed_total 679
telemt_me_writer_restored_same_endpoint_total 16524
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 959
telemt_user_connections_total{user="hello"} 208962
telemt_user_connections_current{user="hello"} 305
telemt_user_octets_from_client{user="hello"} 2653401583 (2.47 GB)
telemt_user_octets_to_client{user="hello"} 74880363731 (69.74 GB)
telemt_user_msgs_from_client{user="hello"} 1159
telemt_user_msgs_to_client{user="hello"} 2341
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 72172.2 (20h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 675715
telemt_connections_bad_total 54124
telemt_handshake_timeouts_total 6701
telemt_upstream_connect_attempt_total 14429
telemt_upstream_connect_success_total 14349
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 14429
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7254
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 20996
telemt_me_reconnect_success_total 10711
telemt_me_reader_eof_total 11676
telemt_me_idle_close_by_peer_total 11676
telemt_me_route_drop_no_conn_total 477544
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 678893
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 921
telemt_desync_full_logged_total 345
telemt_desync_suppressed_total 576
telemt_desync_frames_bucket_total{bucket="1_2"} 235
telemt_desync_frames_bucket_total{bucket="3_10"} 367
telemt_desync_frames_bucket_total{bucket="gt_10"} 319
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 11196
telemt_me_refill_failed_total 319
telemt_me_writer_restored_same_endpoint_total 10697
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 485
telemt_user_connections_total{user="hello"} 580377
telemt_user_connections_current{user="hello"} 910
telemt_user_octets_from_client{user="hello"} 8614519532 (8.02 GB)
telemt_user_octets_to_client{user="hello"} 259893748884 (242.04 GB)
telemt_user_unique_ips_current{user="hello"} 329
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 19939.3 (5h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15928
telemt_connections_bad_total 69
telemt_handshake_timeouts_total 308
telemt_upstream_connect_attempt_total 10973
telemt_upstream_connect_success_total 10886
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 10973
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4893
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 21236
telemt_me_reconnect_success_total 9687
telemt_me_reader_eof_total 10264
telemt_me_idle_close_by_peer_total 10264
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 5817
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15152
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 10143
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 9672
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 456
telemt_user_connections_total{user="hello"} 15250
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 452616097 (431.65 MB)
telemt_user_octets_to_client{user="hello"} 23107911506 (21.52 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 5
```