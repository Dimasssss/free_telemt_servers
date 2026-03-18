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

# Server Metrics 2026-03-18 01:57:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 112341.2 (31h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1302021
telemt_connections_bad_total 9734
telemt_handshake_timeouts_total 32572
telemt_upstream_connect_attempt_total 25010
telemt_upstream_connect_success_total 24507
telemt_upstream_connect_fail_total 503
telemt_upstream_connect_attempts_per_request{bucket="1"} 25010
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12568
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11731
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 503
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 33768
telemt_me_reconnect_success_total 16629
telemt_me_reader_eof_total 18052
telemt_me_idle_close_by_peer_total 18051
telemt_me_route_drop_no_conn_total 566421
telemt_me_route_drop_channel_closed_total 158
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1198519
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7645
telemt_desync_full_logged_total 2257
telemt_desync_suppressed_total 5388
telemt_desync_frames_bucket_total{bucket="1_2"} 2048
telemt_desync_frames_bucket_total{bucket="3_10"} 2899
telemt_desync_frames_bucket_total{bucket="gt_10"} 2698
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 17411
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 16607
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 782
telemt_user_connections_total{user="hello"} 1192731
telemt_user_connections_current{user="hello"} 552
telemt_user_octets_from_client{user="hello"} 23004779787 (21.42 GB)
telemt_user_octets_to_client{user="hello"} 423127149775 (394.07 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 112592.6 (31h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1377230
telemt_connections_bad_total 64215
telemt_handshake_timeouts_total 46865
telemt_upstream_connect_attempt_total 467728
telemt_upstream_connect_success_total 466153
telemt_upstream_connect_fail_total 1574
telemt_upstream_connect_attempts_per_request{bucket="1"} 467727
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 389695
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33102
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43354
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1574
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 123055
telemt_me_reconnect_success_total 17616
telemt_me_reader_eof_total 19774
telemt_me_idle_close_by_peer_total 19761
telemt_me_route_drop_no_conn_total 354873
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 753955
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3503
telemt_desync_full_logged_total 1184
telemt_desync_suppressed_total 2319
telemt_desync_frames_bucket_total{bucket="1_2"} 685
telemt_desync_frames_bucket_total{bucket="3_10"} 1457
telemt_desync_frames_bucket_total{bucket="gt_10"} 1361
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 19181
telemt_me_refill_failed_total 3289
telemt_me_writer_restored_same_endpoint_total 17598
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1565
telemt_user_connections_total{user="hello"} 1196306
telemt_user_connections_current{user="hello"} 598
telemt_user_octets_from_client{user="hello"} 16202054969 (15.09 GB)
telemt_user_octets_to_client{user="hello"} 419036331674 (390.26 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 112368.5 (31h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 824609
telemt_connections_bad_total 56813
telemt_handshake_timeouts_total 24394
telemt_upstream_connect_attempt_total 26281
telemt_upstream_connect_success_total 26129
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 26281
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11978
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14053
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 41186
telemt_me_reconnect_success_total 20495
telemt_me_reader_eof_total 22306
telemt_me_idle_close_by_peer_total 22299
telemt_me_route_drop_no_conn_total 329456
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 697582
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2204
telemt_desync_full_logged_total 717
telemt_desync_suppressed_total 1487
telemt_desync_frames_bucket_total{bucket="1_2"} 625
telemt_desync_frames_bucket_total{bucket="3_10"} 855
telemt_desync_frames_bucket_total{bucket="gt_10"} 724
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 21416
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 20483
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 921
telemt_user_connections_total{user="hello"} 695701
telemt_user_connections_current{user="hello"} 429
telemt_user_octets_from_client{user="hello"} 42244580776 (39.34 GB)
telemt_user_octets_to_client{user="hello"} 308040118032 (286.88 GB)
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 112428.0 (31h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1308088
telemt_connections_bad_total 57465
telemt_handshake_timeouts_total 22057
telemt_upstream_connect_attempt_total 89077
telemt_upstream_connect_success_total 86668
telemt_upstream_connect_fail_total 2409
telemt_upstream_connect_attempts_per_request{bucket="1"} 89077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13723
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 367
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2409
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 36705
telemt_me_reconnect_success_total 16310
telemt_me_reader_eof_total 17973
telemt_me_idle_close_by_peer_total 17971
telemt_me_route_drop_no_conn_total 538391
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1062927
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3959
telemt_desync_full_logged_total 1312
telemt_desync_suppressed_total 2647
telemt_desync_frames_bucket_total{bucket="1_2"} 968
telemt_desync_frames_bucket_total{bucket="3_10"} 1662
telemt_desync_frames_bucket_total{bucket="gt_10"} 1329
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 17254
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 16299
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 944
telemt_user_connections_total{user="hello"} 1126268
telemt_user_connections_current{user="hello"} 513
telemt_user_octets_from_client{user="hello"} 17651133870 (16.44 GB)
telemt_user_octets_to_client{user="hello"} 530353707286 (493.93 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 112400.0 (31h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 865092
telemt_connections_bad_total 100193
telemt_handshake_timeouts_total 6859
telemt_upstream_connect_attempt_total 45851
telemt_upstream_connect_success_total 45223
telemt_upstream_connect_fail_total 628
telemt_upstream_connect_attempts_per_request{bucket="1"} 45851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16528
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 413
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 628
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 58109
telemt_me_reconnect_success_total 23146
telemt_me_reader_eof_total 25099
telemt_me_idle_close_by_peer_total 25096
telemt_me_route_drop_no_conn_total 275485
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 698662
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3214
telemt_desync_full_logged_total 960
telemt_desync_suppressed_total 2254
telemt_desync_frames_bucket_total{bucket="1_2"} 1008
telemt_desync_frames_bucket_total{bucket="3_10"} 1285
telemt_desync_frames_bucket_total{bucket="gt_10"} 921
telemt_pool_swap_total 56
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 24610
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 23138
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1464
telemt_user_connections_total{user="hello"} 715263
telemt_user_connections_current{user="hello"} 493
telemt_user_octets_from_client{user="hello"} 13783672892 (12.84 GB)
telemt_user_octets_to_client{user="hello"} 354332703236 (330.00 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 112560.9 (31h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1113185
telemt_connections_bad_total 116692
telemt_handshake_timeouts_total 9793
telemt_upstream_connect_attempt_total 22385
telemt_upstream_connect_success_total 22257
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 22385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10669
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11469
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 27934
telemt_me_reconnect_success_total 16646
telemt_me_reader_eof_total 18052
telemt_me_idle_close_by_peer_total 18050
telemt_me_route_drop_no_conn_total 765342
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1087926
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2106
telemt_desync_full_logged_total 737
telemt_desync_suppressed_total 1369
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 802
telemt_desync_frames_bucket_total{bucket="gt_10"} 843
telemt_pool_swap_total 99
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 17264
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 16632
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 618
telemt_user_connections_total{user="hello"} 916058
telemt_user_connections_current{user="hello"} 402
telemt_user_octets_from_client{user="hello"} 14850334188 (13.83 GB)
telemt_user_octets_to_client{user="hello"} 397023885100 (369.76 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 60328.2 (16h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 418288
telemt_connections_bad_total 44714
telemt_handshake_timeouts_total 11050
telemt_upstream_connect_attempt_total 22337
telemt_upstream_connect_success_total 22128
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 22337
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11863
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10169
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 30585
telemt_me_reconnect_success_total 18978
telemt_me_reader_eof_total 20068
telemt_me_idle_close_by_peer_total 20068
telemt_me_seq_mismatch_total 26
telemt_me_route_drop_no_conn_total 103805
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 303205
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 30
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1309
telemt_desync_full_logged_total 406
telemt_desync_suppressed_total 903
telemt_desync_frames_bucket_total{bucket="1_2"} 223
telemt_desync_frames_bucket_total{bucket="3_10"} 584
telemt_desync_frames_bucket_total{bucket="gt_10"} 502
telemt_pool_swap_total 39
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19552
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 18942
telemt_me_writer_restored_fallback_total 36
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 574
telemt_user_connections_total{user="hello"} 303141
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 22536502113 (20.99 GB)
telemt_user_octets_to_client{user="hello"} 256972675366 (239.32 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 31
```