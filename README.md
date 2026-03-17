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

# Server Metrics 2026-03-17 12:41:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 64592.7 (17h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 613109
telemt_connections_bad_total 4867
telemt_handshake_timeouts_total 19703
telemt_upstream_connect_attempt_total 15990
telemt_upstream_connect_success_total 15543
telemt_upstream_connect_fail_total 447
telemt_upstream_connect_attempts_per_request{bucket="1"} 15990
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7235
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 447
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 12790
telemt_me_reconnect_success_total 10036
telemt_me_reader_eof_total 10670
telemt_me_idle_close_by_peer_total 10669
telemt_me_route_drop_no_conn_total 199432
telemt_me_route_drop_channel_closed_total 59
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 552922
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4160
telemt_desync_full_logged_total 1119
telemt_desync_suppressed_total 3041
telemt_desync_frames_bucket_total{bucket="1_2"} 1211
telemt_desync_frames_bucket_total{bucket="3_10"} 1721
telemt_desync_frames_bucket_total{bucket="gt_10"} 1228
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 10265
telemt_me_refill_failed_total 81
telemt_me_writer_restored_same_endpoint_total 10014
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 554814
telemt_user_connections_current{user="hello"} 825
telemt_user_octets_from_client{user="hello"} 7568622403 (7.05 GB)
telemt_user_octets_to_client{user="hello"} 199107137095 (185.43 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 299
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 64844.4 (18h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 355332
telemt_connections_bad_total 19849
telemt_handshake_timeouts_total 19882
telemt_upstream_connect_attempt_total 16363
telemt_upstream_connect_success_total 16118
telemt_upstream_connect_fail_total 245
telemt_upstream_connect_attempts_per_request{bucket="1"} 16363
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8937
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 289
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 245
telemt_me_keepalive_timeout_total 176
telemt_me_reconnect_attempts_total 25268
telemt_me_reconnect_success_total 12905
telemt_me_reader_eof_total 13885
telemt_me_idle_close_by_peer_total 13885
telemt_me_route_drop_no_conn_total 132866
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 297360
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1068
telemt_desync_full_logged_total 365
telemt_desync_suppressed_total 703
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 455
telemt_desync_frames_bucket_total{bucket="gt_10"} 353
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 13436
telemt_me_refill_failed_total 384
telemt_me_writer_restored_same_endpoint_total 12889
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 531
telemt_user_connections_total{user="hello"} 297336
telemt_user_connections_current{user="hello"} 642
telemt_user_octets_from_client{user="hello"} 3411442860 (3.18 GB)
telemt_user_octets_to_client{user="hello"} 107373795260 (100.00 GB)
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 64620.3 (17h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 201059
telemt_connections_bad_total 7734
telemt_handshake_timeouts_total 16476
telemt_upstream_connect_attempt_total 16849
telemt_upstream_connect_success_total 16762
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 16849
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7435
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9252
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 15394
telemt_me_reconnect_success_total 13519
telemt_me_reader_eof_total 14440
telemt_me_idle_close_by_peer_total 14440
telemt_me_route_drop_no_conn_total 63131
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 166005
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 638
telemt_desync_full_logged_total 169
telemt_desync_suppressed_total 469
telemt_desync_frames_bucket_total{bucket="1_2"} 257
telemt_desync_frames_bucket_total{bucket="3_10"} 273
telemt_desync_frames_bucket_total{bucket="gt_10"} 108
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 13771
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 13508
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 252
telemt_user_connections_total{user="hello"} 165899
telemt_user_connections_current{user="hello"} 334
telemt_user_octets_from_client{user="hello"} 15161564928 (14.12 GB)
telemt_user_octets_to_client{user="hello"} 45976387636 (42.82 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 64679.5 (17h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 460921
telemt_connections_bad_total 7717
telemt_handshake_timeouts_total 12415
telemt_upstream_connect_attempt_total 15577
telemt_upstream_connect_success_total 15439
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 15577
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7664
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 14563
telemt_me_reconnect_success_total 11189
telemt_me_reader_eof_total 11941
telemt_me_idle_close_by_peer_total 11941
telemt_me_route_drop_no_conn_total 130212
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 387167
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1313
telemt_desync_full_logged_total 465
telemt_desync_suppressed_total 848
telemt_desync_frames_bucket_total{bucket="1_2"} 326
telemt_desync_frames_bucket_total{bucket="3_10"} 588
telemt_desync_frames_bucket_total{bucket="gt_10"} 399
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 11480
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 11180
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 291
telemt_user_connections_total{user="hello"} 388037
telemt_user_connections_current{user="hello"} 838
telemt_user_octets_from_client{user="hello"} 5076261406 (4.73 GB)
telemt_user_octets_to_client{user="hello"} 136538924591 (127.16 GB)
telemt_user_msgs_from_client{user="hello"} 4070
telemt_user_msgs_to_client{user="hello"} 5224
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 64651.5 (17h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 232975
telemt_connections_bad_total 52739
telemt_handshake_timeouts_total 3128
telemt_upstream_connect_attempt_total 18920
telemt_upstream_connect_success_total 18676
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 18920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8350
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10089
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 237
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 28993
telemt_me_reconnect_success_total 15331
telemt_me_reader_eof_total 16388
telemt_me_idle_close_by_peer_total 16388
telemt_me_route_drop_no_conn_total 61996
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 169158
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 987
telemt_desync_full_logged_total 203
telemt_desync_suppressed_total 784
telemt_desync_frames_bucket_total{bucket="1_2"} 507
telemt_desync_frames_bucket_total{bucket="3_10"} 363
telemt_desync_frames_bucket_total{bucket="gt_10"} 117
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 15953
telemt_me_refill_failed_total 424
telemt_me_writer_restored_same_endpoint_total 15323
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 622
telemt_user_connections_total{user="hello"} 169168
telemt_user_connections_current{user="hello"} 323
telemt_user_octets_from_client{user="hello"} 2252218927 (2.10 GB)
telemt_user_octets_to_client{user="hello"} 67791234302 (63.14 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 64812.9 (18h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 554312
telemt_connections_bad_total 52088
telemt_handshake_timeouts_total 5065
telemt_upstream_connect_attempt_total 12965
telemt_upstream_connect_success_total 12896
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 12965
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6377
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6499
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 13580
telemt_me_reconnect_success_total 9685
telemt_me_reader_eof_total 10438
telemt_me_idle_close_by_peer_total 10438
telemt_me_route_drop_no_conn_total 357250
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 545633
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 829
telemt_desync_full_logged_total 303
telemt_desync_suppressed_total 526
telemt_desync_frames_bucket_total{bucket="1_2"} 209
telemt_desync_frames_bucket_total{bucket="3_10"} 317
telemt_desync_frames_bucket_total{bucket="gt_10"} 303
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 9954
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 9671
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 269
telemt_user_connections_total{user="hello"} 467302
telemt_user_connections_current{user="hello"} 940
telemt_user_octets_from_client{user="hello"} 6938419044 (6.46 GB)
telemt_user_octets_to_client{user="hello"} 225880977032 (210.37 GB)
telemt_user_unique_ips_current{user="hello"} 304
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 12579.5 (3h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9687
telemt_connections_bad_total 56
telemt_handshake_timeouts_total 40
telemt_upstream_connect_attempt_total 6836
telemt_upstream_connect_success_total 6775
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 6836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3624
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3150
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 9241
telemt_me_reconnect_success_total 5995
telemt_me_reader_eof_total 6275
telemt_me_idle_close_by_peer_total 6275
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 3587
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9307
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 6150
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 5984
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 9411
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 248398493 (236.89 MB)
telemt_user_octets_to_client{user="hello"} 20174648182 (18.79 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 9
```