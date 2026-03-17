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

# Server Metrics 2026-03-17 12:16:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 63063.9 (17h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 586903
telemt_connections_bad_total 4796
telemt_handshake_timeouts_total 18755
telemt_upstream_connect_attempt_total 15655
telemt_upstream_connect_success_total 15210
telemt_upstream_connect_fail_total 445
telemt_upstream_connect_attempts_per_request{bucket="1"} 15655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8013
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7047
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 445
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 12520
telemt_me_reconnect_success_total 9766
telemt_me_reader_eof_total 10382
telemt_me_idle_close_by_peer_total 10381
telemt_me_route_drop_no_conn_total 190452
telemt_me_route_drop_channel_closed_total 54
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 529070
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4017
telemt_desync_full_logged_total 1071
telemt_desync_suppressed_total 2946
telemt_desync_frames_bucket_total{bucket="1_2"} 1163
telemt_desync_frames_bucket_total{bucket="3_10"} 1669
telemt_desync_frames_bucket_total{bucket="gt_10"} 1185
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 9992
telemt_me_refill_failed_total 81
telemt_me_writer_restored_same_endpoint_total 9744
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 226
telemt_user_connections_total{user="hello"} 530976
telemt_user_connections_current{user="hello"} 949
telemt_user_octets_from_client{user="hello"} 7171213595 (6.68 GB)
telemt_user_octets_to_client{user="hello"} 192858025239 (179.61 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 337
telemt_user_unique_ips_recent_window{user="hello"} 157
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 63314.9 (17h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 334611
telemt_connections_bad_total 16581
telemt_handshake_timeouts_total 19034
telemt_upstream_connect_attempt_total 16053
telemt_upstream_connect_success_total 15830
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 16053
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6800
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8769
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 261
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 25014
telemt_me_reconnect_success_total 12679
telemt_me_reader_eof_total 13675
telemt_me_idle_close_by_peer_total 13675
telemt_me_route_drop_no_conn_total 122496
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 281444
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 988
telemt_desync_full_logged_total 339
telemt_desync_suppressed_total 649
telemt_desync_frames_bucket_total{bucket="1_2"} 248
telemt_desync_frames_bucket_total{bucket="3_10"} 415
telemt_desync_frames_bucket_total{bucket="gt_10"} 325
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 13202
telemt_me_refill_failed_total 384
telemt_me_writer_restored_same_endpoint_total 12663
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 523
telemt_user_connections_total{user="hello"} 281429
telemt_user_connections_current{user="hello"} 617
telemt_user_octets_from_client{user="hello"} 3238837908 (3.02 GB)
telemt_user_octets_to_client{user="hello"} 102327234244 (95.30 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 63091.0 (17h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 192258
telemt_connections_bad_total 7725
telemt_handshake_timeouts_total 16093
telemt_upstream_connect_attempt_total 16522
telemt_upstream_connect_success_total 16435
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 16522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7289
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9071
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 15116
telemt_me_reconnect_success_total 13242
telemt_me_reader_eof_total 14145
telemt_me_idle_close_by_peer_total 14145
telemt_me_route_drop_no_conn_total 57380
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 157766
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 595
telemt_desync_full_logged_total 156
telemt_desync_suppressed_total 439
telemt_desync_frames_bucket_total{bucket="1_2"} 242
telemt_desync_frames_bucket_total{bucket="3_10"} 256
telemt_desync_frames_bucket_total{bucket="gt_10"} 97
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 13491
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 13231
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 249
telemt_user_connections_total{user="hello"} 157663
telemt_user_connections_current{user="hello"} 330
telemt_user_octets_from_client{user="hello"} 14942840184 (13.92 GB)
telemt_user_octets_to_client{user="hello"} 44539873000 (41.48 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 63150.2 (17h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 438469
telemt_connections_bad_total 7229
telemt_handshake_timeouts_total 12295
telemt_upstream_connect_attempt_total 15253
telemt_upstream_connect_success_total 15117
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 15253
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7486
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7533
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 14355
telemt_me_reconnect_success_total 10985
telemt_me_reader_eof_total 11731
telemt_me_idle_close_by_peer_total 11731
telemt_me_route_drop_no_conn_total 124081
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 366614
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1175
telemt_desync_full_logged_total 423
telemt_desync_suppressed_total 752
telemt_desync_frames_bucket_total{bucket="1_2"} 288
telemt_desync_frames_bucket_total{bucket="3_10"} 515
telemt_desync_frames_bucket_total{bucket="gt_10"} 372
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 11269
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 10976
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 284
telemt_user_connections_total{user="hello"} 367427
telemt_user_connections_current{user="hello"} 852
telemt_user_octets_from_client{user="hello"} 4857954061 (4.52 GB)
telemt_user_octets_to_client{user="hello"} 131449725725 (122.42 GB)
telemt_user_msgs_from_client{user="hello"} 3934
telemt_user_msgs_to_client{user="hello"} 4814
telemt_user_unique_ips_current{user="hello"} 228
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 63121.9 (17h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 224796
telemt_connections_bad_total 52466
telemt_handshake_timeouts_total 3105
telemt_upstream_connect_attempt_total 18464
telemt_upstream_connect_success_total 18222
telemt_upstream_connect_fail_total 242
telemt_upstream_connect_attempts_per_request{bucket="1"} 18464
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9824
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 237
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 242
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 28584
telemt_me_reconnect_success_total 14925
telemt_me_reader_eof_total 15976
telemt_me_idle_close_by_peer_total 15976
telemt_me_route_drop_no_conn_total 59215
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161603
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 941
telemt_desync_full_logged_total 188
telemt_desync_suppressed_total 753
telemt_desync_frames_bucket_total{bucket="1_2"} 491
telemt_desync_frames_bucket_total{bucket="3_10"} 346
telemt_desync_frames_bucket_total{bucket="gt_10"} 104
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 15539
telemt_me_refill_failed_total 424
telemt_me_writer_restored_same_endpoint_total 14917
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 614
telemt_user_connections_total{user="hello"} 161617
telemt_user_connections_current{user="hello"} 295
telemt_user_octets_from_client{user="hello"} 2185458327 (2.04 GB)
telemt_user_octets_to_client{user="hello"} 66449943914 (61.89 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 63283.5 (17h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 532569
telemt_connections_bad_total 52031
telemt_handshake_timeouts_total 4922
telemt_upstream_connect_attempt_total 12758
telemt_upstream_connect_success_total 12689
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 12758
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6279
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6390
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 13416
telemt_me_reconnect_success_total 9521
telemt_me_reader_eof_total 10268
telemt_me_idle_close_by_peer_total 10268
telemt_me_route_drop_no_conn_total 348575
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 524880
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 796
telemt_desync_full_logged_total 293
telemt_desync_suppressed_total 503
telemt_desync_frames_bucket_total{bucket="1_2"} 205
telemt_desync_frames_bucket_total{bucket="3_10"} 304
telemt_desync_frames_bucket_total{bucket="gt_10"} 287
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 9789
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 9507
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 268
telemt_user_connections_total{user="hello"} 446566
telemt_user_connections_current{user="hello"} 949
telemt_user_octets_from_client{user="hello"} 6687987508 (6.23 GB)
telemt_user_octets_to_client{user="hello"} 218414004556 (203.41 GB)
telemt_user_unique_ips_current{user="hello"} 317
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 11050.0 (3h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8642
telemt_connections_bad_total 46
telemt_handshake_timeouts_total 37
telemt_upstream_connect_attempt_total 6149
telemt_upstream_connect_success_total 6092
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 6149
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2811
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 8601
telemt_me_reconnect_success_total 5358
telemt_me_reader_eof_total 5638
telemt_me_idle_close_by_peer_total 5638
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 3238
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8284
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 5510
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 5349
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 152
telemt_user_connections_total{user="hello"} 8390
telemt_user_connections_current{user="hello"} 83
telemt_user_octets_from_client{user="hello"} 175517553 (167.39 MB)
telemt_user_octets_to_client{user="hello"} 19675285322 (18.32 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 8
```