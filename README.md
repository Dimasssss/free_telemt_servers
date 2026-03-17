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

# Server Metrics 2026-03-17 13:43:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 68263.9 (18h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 686297
telemt_connections_bad_total 5531
telemt_handshake_timeouts_total 20472
telemt_upstream_connect_attempt_total 16787
telemt_upstream_connect_success_total 16334
telemt_upstream_connect_fail_total 453
telemt_upstream_connect_attempts_per_request{bucket="1"} 16787
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8529
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7655
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 453
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 17174
telemt_me_reconnect_success_total 10641
telemt_me_reader_eof_total 11401
telemt_me_idle_close_by_peer_total 11400
telemt_me_route_drop_no_conn_total 237653
telemt_me_route_drop_channel_closed_total 71
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 621795
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4505
telemt_desync_full_logged_total 1250
telemt_desync_suppressed_total 3255
telemt_desync_frames_bucket_total{bucket="1_2"} 1278
telemt_desync_frames_bucket_total{bucket="3_10"} 1848
telemt_desync_frames_bucket_total{bucket="gt_10"} 1379
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 10997
telemt_me_refill_failed_total 199
telemt_me_writer_restored_same_endpoint_total 10619
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 356
telemt_user_connections_total{user="hello"} 623686
telemt_user_connections_current{user="hello"} 986
telemt_user_octets_from_client{user="hello"} 10032859087 (9.34 GB)
telemt_user_octets_to_client{user="hello"} 218337520615 (203.34 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 330
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 68515.5 (19h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 422943
telemt_connections_bad_total 25458
telemt_handshake_timeouts_total 21367
telemt_upstream_connect_attempt_total 18004
telemt_upstream_connect_success_total 17718
telemt_upstream_connect_fail_total 286
telemt_upstream_connect_attempts_per_request{bucket="1"} 18004
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8047
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9210
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 461
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 286
telemt_me_keepalive_timeout_total 262
telemt_me_reconnect_attempts_total 29005
telemt_me_reconnect_success_total 13292
telemt_me_reader_eof_total 14356
telemt_me_idle_close_by_peer_total 14356
telemt_me_route_drop_no_conn_total 183077
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 353703
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1413
telemt_desync_full_logged_total 447
telemt_desync_suppressed_total 966
telemt_desync_frames_bucket_total{bucket="1_2"} 313
telemt_desync_frames_bucket_total{bucket="3_10"} 616
telemt_desync_frames_bucket_total{bucket="gt_10"} 484
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 13947
telemt_me_refill_failed_total 487
telemt_me_writer_restored_same_endpoint_total 13276
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 655
telemt_user_connections_total{user="hello"} 354608
telemt_user_connections_current{user="hello"} 602
telemt_user_octets_from_client{user="hello"} 3809654811 (3.55 GB)
telemt_user_octets_to_client{user="hello"} 117881376123 (109.79 GB)
telemt_user_msgs_from_client{user="hello"} 2850
telemt_user_msgs_to_client{user="hello"} 6435
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 68291.0 (18h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 225881
telemt_connections_bad_total 7796
telemt_handshake_timeouts_total 16694
telemt_upstream_connect_attempt_total 18064
telemt_upstream_connect_success_total 17974
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 18064
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7987
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9911
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 18936
telemt_me_reconnect_success_total 14527
telemt_me_reader_eof_total 15539
telemt_me_idle_close_by_peer_total 15539
telemt_me_route_drop_no_conn_total 83474
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 189617
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 732
telemt_desync_full_logged_total 204
telemt_desync_suppressed_total 528
telemt_desync_frames_bucket_total{bucket="1_2"} 273
telemt_desync_frames_bucket_total{bucket="3_10"} 321
telemt_desync_frames_bucket_total{bucket="gt_10"} 138
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 14869
telemt_me_refill_failed_total 135
telemt_me_writer_restored_same_endpoint_total 14516
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 342
telemt_user_connections_total{user="hello"} 189501
telemt_user_connections_current{user="hello"} 278
telemt_user_octets_from_client{user="hello"} 15293536268 (14.24 GB)
telemt_user_octets_to_client{user="hello"} 51926037092 (48.36 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 68350.7 (18h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 515627
telemt_connections_bad_total 8066
telemt_handshake_timeouts_total 12799
telemt_upstream_connect_attempt_total 16287
telemt_upstream_connect_success_total 16140
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 16287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8058
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7966
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 18337
telemt_me_reconnect_success_total 11688
telemt_me_reader_eof_total 12559
telemt_me_idle_close_by_peer_total 12559
telemt_me_route_drop_no_conn_total 152567
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 437691
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1556
telemt_desync_full_logged_total 536
telemt_desync_suppressed_total 1020
telemt_desync_frames_bucket_total{bucket="1_2"} 379
telemt_desync_frames_bucket_total{bucket="3_10"} 698
telemt_desync_frames_bucket_total{bucket="gt_10"} 479
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12101
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 11679
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 413
telemt_user_connections_total{user="hello"} 438566
telemt_user_connections_current{user="hello"} 808
telemt_user_octets_from_client{user="hello"} 5560978682 (5.18 GB)
telemt_user_octets_to_client{user="hello"} 148519249327 (138.32 GB)
telemt_user_msgs_from_client{user="hello"} 4070
telemt_user_msgs_to_client{user="hello"} 5224
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 68322.5 (18h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 255737
telemt_connections_bad_total 56342
telemt_handshake_timeouts_total 3259
telemt_upstream_connect_attempt_total 19530
telemt_upstream_connect_success_total 19274
telemt_upstream_connect_fail_total 256
telemt_upstream_connect_attempts_per_request{bucket="1"} 19530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10437
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 245
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 256
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 34327
telemt_me_reconnect_success_total 15735
telemt_me_reader_eof_total 16950
telemt_me_idle_close_by_peer_total 16950
telemt_me_route_drop_no_conn_total 67946
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 186477
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1092
telemt_desync_full_logged_total 228
telemt_desync_suppressed_total 864
telemt_desync_frames_bucket_total{bucket="1_2"} 545
telemt_desync_frames_bucket_total{bucket="3_10"} 418
telemt_desync_frames_bucket_total{bucket="gt_10"} 129
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 16521
telemt_me_refill_failed_total 578
telemt_me_writer_restored_same_endpoint_total 15727
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 786
telemt_user_connections_total{user="hello"} 186640
telemt_user_connections_current{user="hello"} 312
telemt_user_octets_from_client{user="hello"} 2504488279 (2.33 GB)
telemt_user_octets_to_client{user="hello"} 71259426262 (66.37 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 68484.0 (19h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 613360
telemt_connections_bad_total 53259
telemt_handshake_timeouts_total 6066
telemt_upstream_connect_attempt_total 13871
telemt_upstream_connect_success_total 13796
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 13871
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6956
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 37
telemt_me_reconnect_attempts_total 16678
telemt_me_reconnect_success_total 10367
telemt_me_reader_eof_total 11205
telemt_me_idle_close_by_peer_total 11205
telemt_me_route_drop_no_conn_total 421040
telemt_me_route_drop_channel_closed_total 35
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 617476
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 838
telemt_desync_full_logged_total 308
telemt_desync_suppressed_total 530
telemt_desync_frames_bucket_total{bucket="1_2"} 210
telemt_desync_frames_bucket_total{bucket="3_10"} 322
telemt_desync_frames_bucket_total{bucket="gt_10"} 306
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 10723
telemt_me_refill_failed_total 195
telemt_me_writer_restored_same_endpoint_total 10353
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 356
telemt_user_connections_total{user="hello"} 522366
telemt_user_connections_current{user="hello"} 916
telemt_user_octets_from_client{user="hello"} 7826211020 (7.29 GB)
telemt_user_octets_to_client{user="hello"} 246620119508 (229.68 GB)
telemt_user_unique_ips_current{user="hello"} 312
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 16250.6 (4h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12758
telemt_connections_bad_total 58
telemt_handshake_timeouts_total 48
telemt_upstream_connect_attempt_total 9213
telemt_upstream_connect_success_total 9139
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 9212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4927
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4205
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 14774
telemt_me_reconnect_success_total 8160
telemt_me_reader_eof_total 8561
telemt_me_idle_close_by_peer_total 8561
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 4351
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12338
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 8444
telemt_me_refill_failed_total 205
telemt_me_writer_restored_same_endpoint_total 8146
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 284
telemt_user_connections_total{user="hello"} 12439
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 353497669 (337.12 MB)
telemt_user_octets_to_client{user="hello"} 21908585470 (20.40 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 10
```