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

# Server Metrics 2026-03-17 11:13:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 59274.4 (16h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 520617
telemt_connections_bad_total 4327
telemt_handshake_timeouts_total 15669
telemt_upstream_connect_attempt_total 14652
telemt_upstream_connect_success_total 14215
telemt_upstream_connect_fail_total 437
telemt_upstream_connect_attempts_per_request{bucket="1"} 14652
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6537
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 437
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 10511
telemt_me_reconnect_success_total 8977
telemt_me_reader_eof_total 9543
telemt_me_idle_close_by_peer_total 9542
telemt_me_route_drop_no_conn_total 171359
telemt_me_route_drop_channel_closed_total 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 471000
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3739
telemt_desync_full_logged_total 984
telemt_desync_suppressed_total 2755
telemt_desync_frames_bucket_total{bucket="1_2"} 1058
telemt_desync_frames_bucket_total{bucket="3_10"} 1570
telemt_desync_frames_bucket_total{bucket="gt_10"} 1111
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 9160
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 8955
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 472941
telemt_user_connections_current{user="hello"} 946
telemt_user_octets_from_client{user="hello"} 6527563707 (6.08 GB)
telemt_user_octets_to_client{user="hello"} 175174143491 (163.14 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 338
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 59526.7 (16h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 290319
telemt_connections_bad_total 9625
telemt_handshake_timeouts_total 17260
telemt_upstream_connect_attempt_total 15193
telemt_upstream_connect_success_total 14975
telemt_upstream_connect_fail_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 15193
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8317
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 195
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 218
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 23118
telemt_me_reconnect_success_total 12002
telemt_me_reader_eof_total 12928
telemt_me_idle_close_by_peer_total 12928
telemt_me_route_drop_no_conn_total 108495
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 249112
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 728
telemt_desync_full_logged_total 265
telemt_desync_suppressed_total 463
telemt_desync_frames_bucket_total{bucket="1_2"} 210
telemt_desync_frames_bucket_total{bucket="3_10"} 314
telemt_desync_frames_bucket_total{bucket="gt_10"} 204
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 12479
telemt_me_refill_failed_total 346
telemt_me_writer_restored_same_endpoint_total 11986
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 477
telemt_user_connections_total{user="hello"} 249100
telemt_user_connections_current{user="hello"} 557
telemt_user_octets_from_client{user="hello"} 2955929972 (2.75 GB)
telemt_user_octets_to_client{user="hello"} 90151615620 (83.96 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 59302.3 (16h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 171822
telemt_connections_bad_total 7639
telemt_handshake_timeouts_total 13605
telemt_upstream_connect_attempt_total 15618
telemt_upstream_connect_success_total 15537
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 15618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6862
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8607
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 14432
telemt_me_reconnect_success_total 12562
telemt_me_reader_eof_total 13425
telemt_me_idle_close_by_peer_total 13425
telemt_me_route_drop_no_conn_total 50919
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 140465
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 517
telemt_desync_full_logged_total 132
telemt_desync_suppressed_total 385
telemt_desync_frames_bucket_total{bucket="1_2"} 224
telemt_desync_frames_bucket_total{bucket="3_10"} 217
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12789
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 12551
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 227
telemt_user_connections_total{user="hello"} 140369
telemt_user_connections_current{user="hello"} 334
telemt_user_octets_from_client{user="hello"} 12906089104 (12.02 GB)
telemt_user_octets_to_client{user="hello"} 41279995464 (38.44 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 59360.8 (16h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 386261
telemt_connections_bad_total 6691
telemt_handshake_timeouts_total 11949
telemt_upstream_connect_attempt_total 13426
telemt_upstream_connect_success_total 13301
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 13426
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6953
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 11391
telemt_me_reconnect_success_total 10289
telemt_me_reader_eof_total 10938
telemt_me_idle_close_by_peer_total 10938
telemt_me_route_drop_no_conn_total 108335
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 319290
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 901
telemt_desync_full_logged_total 327
telemt_desync_suppressed_total 574
telemt_desync_frames_bucket_total{bucket="1_2"} 217
telemt_desync_frames_bucket_total{bucket="3_10"} 386
telemt_desync_frames_bucket_total{bucket="gt_10"} 298
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 10489
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 10281
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 200
telemt_user_connections_total{user="hello"} 319230
telemt_user_connections_current{user="hello"} 680
telemt_user_octets_from_client{user="hello"} 4148042694 (3.86 GB)
telemt_user_octets_to_client{user="hello"} 118391596009 (110.26 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 59332.8 (16h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 205642
telemt_connections_bad_total 51778
telemt_handshake_timeouts_total 2991
telemt_upstream_connect_attempt_total 17674
telemt_upstream_connect_success_total 17442
telemt_upstream_connect_fail_total 232
telemt_upstream_connect_attempts_per_request{bucket="1"} 17674
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7804
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9427
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 232
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 26646
telemt_me_reconnect_success_total 14370
telemt_me_reader_eof_total 15352
telemt_me_idle_close_by_peer_total 15352
telemt_me_route_drop_no_conn_total 54131
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 144301
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 807
telemt_desync_full_logged_total 157
telemt_desync_suppressed_total 650
telemt_desync_frames_bucket_total{bucket="1_2"} 422
telemt_desync_frames_bucket_total{bucket="3_10"} 294
telemt_desync_frames_bucket_total{bucket="gt_10"} 91
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 14931
telemt_me_refill_failed_total 381
telemt_me_writer_restored_same_endpoint_total 14362
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 561
telemt_user_connections_total{user="hello"} 144323
telemt_user_connections_current{user="hello"} 287
telemt_user_octets_from_client{user="hello"} 2055427563 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 62566009970 (58.27 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 59494.7 (16h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 482455
telemt_connections_bad_total 51630
telemt_handshake_timeouts_total 4642
telemt_upstream_connect_attempt_total 12112
telemt_upstream_connect_success_total 12046
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 12112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5958
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6068
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 12951
telemt_me_reconnect_success_total 9059
telemt_me_reader_eof_total 9758
telemt_me_idle_close_by_peer_total 9758
telemt_me_route_drop_no_conn_total 327762
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 477317
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 713
telemt_desync_full_logged_total 268
telemt_desync_suppressed_total 445
telemt_desync_frames_bucket_total{bucket="1_2"} 192
telemt_desync_frames_bucket_total{bucket="3_10"} 273
telemt_desync_frames_bucket_total{bucket="gt_10"} 248
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 9321
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 9045
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 262
telemt_user_connections_total{user="hello"} 399017
telemt_user_connections_current{user="hello"} 931
telemt_user_octets_from_client{user="hello"} 5855374088 (5.45 GB)
telemt_user_octets_to_client{user="hello"} 203436089036 (189.46 GB)
telemt_user_unique_ips_current{user="hello"} 297
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 7260.8 (2h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5481
telemt_connections_bad_total 33
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 3767
telemt_upstream_connect_success_total 3728
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 3767
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1762
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 3238
telemt_me_reconnect_success_total 3203
telemt_me_reader_eof_total 3295
telemt_me_idle_close_by_peer_total 3295
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 2197
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5176
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 3237
telemt_me_writer_restored_same_endpoint_total 3194
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 5283
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 140475741 (133.97 MB)
telemt_user_octets_to_client{user="hello"} 18308563158 (17.05 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 6
```