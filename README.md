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

# Server Metrics 2026-03-17 14:18:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 70418.7 (19h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 738212
telemt_connections_bad_total 5707
telemt_handshake_timeouts_total 21640
telemt_upstream_connect_attempt_total 17173
telemt_upstream_connect_success_total 16716
telemt_upstream_connect_fail_total 457
telemt_upstream_connect_attempts_per_request{bucket="1"} 17173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8758
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7808
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 457
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 20768
telemt_me_reconnect_success_total 10875
telemt_me_reader_eof_total 11738
telemt_me_idle_close_by_peer_total 11737
telemt_me_route_drop_no_conn_total 292263
telemt_me_route_drop_channel_closed_total 74
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 669672
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4646
telemt_desync_full_logged_total 1312
telemt_desync_suppressed_total 3334
telemt_desync_frames_bucket_total{bucket="1_2"} 1299
telemt_desync_frames_bucket_total{bucket="3_10"} 1900
telemt_desync_frames_bucket_total{bucket="gt_10"} 1447
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 11337
telemt_me_refill_failed_total 304
telemt_me_writer_restored_same_endpoint_total 10853
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 462
telemt_user_connections_total{user="hello"} 671551
telemt_user_connections_current{user="hello"} 960
telemt_user_octets_from_client{user="hello"} 11123532291 (10.36 GB)
telemt_user_octets_to_client{user="hello"} 226529171955 (210.97 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 343
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 70670.1 (19h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 462805
telemt_connections_bad_total 29384
telemt_handshake_timeouts_total 23124
telemt_upstream_connect_attempt_total 45055
telemt_upstream_connect_success_total 44639
telemt_upstream_connect_fail_total 413
telemt_upstream_connect_attempts_per_request{bucket="1"} 45052
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30733
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10505
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3401
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 413
telemt_me_keepalive_timeout_total 326
telemt_me_reconnect_attempts_total 33115
telemt_me_reconnect_success_total 13365
telemt_me_reader_eof_total 14542
telemt_me_idle_close_by_peer_total 14542
telemt_me_route_drop_no_conn_total 188259
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 360021
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1437
telemt_desync_full_logged_total 452
telemt_desync_suppressed_total 985
telemt_desync_frames_bucket_total{bucket="1_2"} 321
telemt_desync_frames_bucket_total{bucket="3_10"} 627
telemt_desync_frames_bucket_total{bucket="gt_10"} 489
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14145
telemt_me_refill_failed_total 613
telemt_me_writer_restored_same_endpoint_total 13349
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 780
telemt_user_connections_total{user="hello"} 387650
telemt_user_connections_current{user="hello"} 660
telemt_user_octets_from_client{user="hello"} 4222442799 (3.93 GB)
telemt_user_octets_to_client{user="hello"} 121956693212 (113.58 GB)
telemt_user_msgs_from_client{user="hello"} 414584
telemt_user_msgs_to_client{user="hello"} 1259535
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 70445.6 (19h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 241826
telemt_connections_bad_total 7810
telemt_handshake_timeouts_total 16961
telemt_upstream_connect_attempt_total 18629
telemt_upstream_connect_success_total 18535
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 18629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8273
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10183
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 23261
telemt_me_reconnect_success_total 14947
telemt_me_reader_eof_total 16077
telemt_me_idle_close_by_peer_total 16074
telemt_me_route_drop_no_conn_total 99446
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 204451
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 753
telemt_desync_full_logged_total 217
telemt_desync_suppressed_total 536
telemt_desync_frames_bucket_total{bucket="1_2"} 275
telemt_desync_frames_bucket_total{bucket="3_10"} 336
telemt_desync_frames_bucket_total{bucket="gt_10"} 142
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 15414
telemt_me_refill_failed_total 257
telemt_me_writer_restored_same_endpoint_total 14936
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 467
telemt_user_connections_total{user="hello"} 204323
telemt_user_connections_current{user="hello"} 343
telemt_user_octets_from_client{user="hello"} 15581446224 (14.51 GB)
telemt_user_octets_to_client{user="hello"} 53562730888 (49.88 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 70505.1 (19h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 561594
telemt_connections_bad_total 8103
telemt_handshake_timeouts_total 13069
telemt_upstream_connect_attempt_total 16560
telemt_upstream_connect_success_total 16407
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 16560
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8074
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 22557
telemt_me_reconnect_success_total 11809
telemt_me_reader_eof_total 12802
telemt_me_idle_close_by_peer_total 12802
telemt_me_route_drop_no_conn_total 201195
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 481137
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1636
telemt_desync_full_logged_total 563
telemt_desync_suppressed_total 1073
telemt_desync_frames_bucket_total{bucket="1_2"} 411
telemt_desync_frames_bucket_total{bucket="3_10"} 737
telemt_desync_frames_bucket_total{bucket="gt_10"} 488
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12350
telemt_me_refill_failed_total 331
telemt_me_writer_restored_same_endpoint_total 11800
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 541
telemt_user_connections_total{user="hello"} 481968
telemt_user_connections_current{user="hello"} 764
telemt_user_octets_from_client{user="hello"} 5985097710 (5.57 GB)
telemt_user_octets_to_client{user="hello"} 157626408463 (146.80 GB)
telemt_user_msgs_from_client{user="hello"} 4070
telemt_user_msgs_to_client{user="hello"} 5224
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 70477.0 (19h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 271422
telemt_connections_bad_total 56726
telemt_handshake_timeouts_total 3439
telemt_upstream_connect_attempt_total 20650
telemt_upstream_connect_success_total 20195
telemt_upstream_connect_fail_total 455
telemt_upstream_connect_attempts_per_request{bucket="1"} 20650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9128
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10786
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 281
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 455
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 36741
telemt_me_reconnect_success_total 16242
telemt_me_reader_eof_total 17472
telemt_me_idle_close_by_peer_total 17470
telemt_me_route_drop_no_conn_total 76757
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 200036
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1095
telemt_desync_full_logged_total 229
telemt_desync_suppressed_total 866
telemt_desync_frames_bucket_total{bucket="1_2"} 546
telemt_desync_frames_bucket_total{bucket="3_10"} 420
telemt_desync_frames_bucket_total{bucket="gt_10"} 129
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 17157
telemt_me_refill_failed_total 636
telemt_me_writer_restored_same_endpoint_total 16234
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 915
telemt_user_connections_total{user="hello"} 200493
telemt_user_connections_current{user="hello"} 245
telemt_user_octets_from_client{user="hello"} 2575710439 (2.40 GB)
telemt_user_octets_to_client{user="hello"} 73101907651 (68.08 GB)
telemt_user_msgs_from_client{user="hello"} 1159
telemt_user_msgs_to_client{user="hello"} 2341
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 70638.7 (19h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 651712
telemt_connections_bad_total 53845
telemt_handshake_timeouts_total 6472
telemt_upstream_connect_attempt_total 14153
telemt_upstream_connect_success_total 14078
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 14153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6942
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7113
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 20814
telemt_me_reconnect_success_total 10534
telemt_me_reader_eof_total 11496
telemt_me_idle_close_by_peer_total 11496
telemt_me_route_drop_no_conn_total 455939
telemt_me_route_drop_channel_closed_total 35
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 653616
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 867
telemt_desync_full_logged_total 323
telemt_desync_suppressed_total 544
telemt_desync_frames_bucket_total{bucket="1_2"} 220
telemt_desync_frames_bucket_total{bucket="3_10"} 335
telemt_desync_frames_bucket_total{bucket="gt_10"} 312
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 11018
telemt_me_refill_failed_total 319
telemt_me_writer_restored_same_endpoint_total 10520
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 484
telemt_user_connections_total{user="hello"} 558095
telemt_user_connections_current{user="hello"} 884
telemt_user_octets_from_client{user="hello"} 8386160044 (7.81 GB)
telemt_user_octets_to_client{user="hello"} 254030553348 (236.58 GB)
telemt_user_unique_ips_current{user="hello"} 307
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 18405.1 (5h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14904
telemt_connections_bad_total 63
telemt_handshake_timeouts_total 266
telemt_upstream_connect_attempt_total 10365
telemt_upstream_connect_success_total 10283
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 10365
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5620
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4654
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 19440
telemt_me_reconnect_success_total 9175
telemt_me_reader_eof_total 9697
telemt_me_idle_close_by_peer_total 9697
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 5207
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14181
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 9585
telemt_me_refill_failed_total 319
telemt_me_writer_restored_same_endpoint_total 9160
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 410
telemt_user_connections_total{user="hello"} 14282
telemt_user_connections_current{user="hello"} 66
telemt_user_octets_from_client{user="hello"} 398090029 (379.65 MB)
telemt_user_octets_to_client{user="hello"} 22625348486 (21.07 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 9
```