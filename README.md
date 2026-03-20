# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

**Принимаю донаты криптой для добавления и продления серверов:**  
- TON: UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
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

# Server Metrics 2026-03-20 06:50:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 48759.4 (13h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 990037
telemt_connections_bad_total 60676
telemt_connections_current 1633
telemt_connections_me_current 1633
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 26047
telemt_upstream_connect_attempt_total 9426
telemt_upstream_connect_success_total 9320
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 9426
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4189
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 5812
telemt_me_reconnect_success_total 5768
telemt_me_reader_eof_total 6113
telemt_me_idle_close_by_peer_total 6112
telemt_me_route_drop_no_conn_total 284363
telemt_me_route_drop_channel_closed_total 106
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 808103
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4193
telemt_desync_full_logged_total 1519
telemt_desync_suppressed_total 2674
telemt_desync_frames_bucket_total{bucket="1_2"} 831
telemt_desync_frames_bucket_total{bucket="3_10"} 1627
telemt_desync_frames_bucket_total{bucket="gt_10"} 1735
telemt_pool_swap_total 53
telemt_me_writer_close_signal_drop_total 50
telemt_me_writer_removed_unexpected_total 5831
telemt_me_writer_restored_same_endpoint_total 5755
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 807492
telemt_user_connections_current{user="hello"} 1633
telemt_user_octets_from_client{user="hello"} 34396590360 (32.03 GB)
telemt_user_octets_to_client{user="hello"} 277870172005 (258.79 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 579
telemt_user_unique_ips_recent_window{user="hello"} 218
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 65214.7 (18h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4397969
telemt_connections_bad_total 417241
telemt_connections_current 5352
telemt_connections_me_current 5352
telemt_handshake_timeouts_total 98853
telemt_upstream_connect_attempt_total 12222
telemt_upstream_connect_success_total 11997
telemt_upstream_connect_fail_total 225
telemt_upstream_connect_attempts_per_request{bucket="1"} 12222
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5178
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 225
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 11785
telemt_me_reconnect_success_total 7528
telemt_me_reader_eof_total 8055
telemt_me_idle_close_by_peer_total 8054
telemt_me_route_drop_no_conn_total 2112714
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3591567
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14038
telemt_desync_full_logged_total 4679
telemt_desync_suppressed_total 9359
telemt_desync_frames_bucket_total{bucket="1_2"} 2791
telemt_desync_frames_bucket_total{bucket="3_10"} 5463
telemt_desync_frames_bucket_total{bucket="gt_10"} 5784
telemt_pool_swap_total 58
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 73
telemt_me_writer_removed_unexpected_total 7761
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 7473
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 233
telemt_user_connections_total{user="hello"} 3591203
telemt_user_connections_current{user="hello"} 5352
telemt_user_octets_from_client{user="hello"} 51689654482 (48.14 GB)
telemt_user_octets_to_client{user="hello"} 1311595168126 (1.19 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1751
telemt_user_unique_ips_recent_window{user="hello"} 696
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 65192.7 (18h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4007350
telemt_connections_bad_total 519352
telemt_connections_current 3517
telemt_connections_me_current 3517
telemt_handshake_timeouts_total 63197
telemt_upstream_connect_attempt_total 12051
telemt_upstream_connect_success_total 11947
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 12051
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5522
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 3075
telemt_me_reconnect_attempts_total 8195
telemt_me_reconnect_success_total 7235
telemt_me_reader_eof_total 7565
telemt_me_idle_close_by_peer_total 7561
telemt_me_route_drop_no_conn_total 2708258
telemt_me_route_drop_channel_closed_total 250
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2874134
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 179
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9870
telemt_desync_full_logged_total 3095
telemt_desync_suppressed_total 6775
telemt_desync_frames_bucket_total{bucket="1_2"} 2442
telemt_desync_frames_bucket_total{bucket="3_10"} 3787
telemt_desync_frames_bucket_total{bucket="gt_10"} 3641
telemt_pool_swap_total 64
telemt_me_writer_close_signal_drop_total 308
telemt_me_writer_removed_unexpected_total 7329
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 7234
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 2880518
telemt_user_connections_current{user="hello"} 3517
telemt_user_octets_from_client{user="hello"} 40083296422 (37.33 GB)
telemt_user_octets_to_client{user="hello"} 1077759925636 (1003.74 GB)
telemt_user_msgs_from_client{user="hello"} 2664
telemt_user_msgs_to_client{user="hello"} 1842
telemt_user_unique_ips_current{user="hello"} 1186
telemt_user_unique_ips_recent_window{user="hello"} 474
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 65180.2 (18h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4100653
telemt_connections_bad_total 274804
telemt_connections_current 4328
telemt_connections_me_current 4328
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 58955
telemt_upstream_connect_attempt_total 67847
telemt_upstream_connect_success_total 63113
telemt_upstream_connect_fail_total 4734
telemt_upstream_connect_attempts_per_request{bucket="1"} 67847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52599
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9777
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 712
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4734
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 10452
telemt_me_reconnect_success_total 7469
telemt_me_reader_eof_total 7802
telemt_me_idle_close_by_peer_total 7801
telemt_me_route_drop_no_conn_total 4078753
telemt_me_route_drop_channel_closed_total 76
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3403374
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11781
telemt_desync_full_logged_total 3531
telemt_desync_suppressed_total 8250
telemt_desync_frames_bucket_total{bucket="1_2"} 2742
telemt_desync_frames_bucket_total{bucket="3_10"} 4575
telemt_desync_frames_bucket_total{bucket="gt_10"} 4464
telemt_pool_swap_total 53
telemt_me_writer_close_signal_drop_total 676
telemt_me_writer_removed_unexpected_total 8195
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 7465
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 410
telemt_me_writer_removed_unexpected_minus_restored_total 726
telemt_user_connections_total{user="hello"} 3454425
telemt_user_connections_current{user="hello"} 4328
telemt_user_octets_from_client{user="hello"} 44655569112 (41.59 GB)
telemt_user_octets_to_client{user="hello"} 834793496339 (777.46 GB)
telemt_user_msgs_from_client{user="hello"} 260491
telemt_user_msgs_to_client{user="hello"} 1782062
telemt_user_unique_ips_current{user="hello"} 1354
telemt_user_unique_ips_recent_window{user="hello"} 680
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 2763.5 (0h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 340345
telemt_connections_bad_total 40673
telemt_connections_current 4621
telemt_connections_me_current 4621
telemt_handshake_timeouts_total 7440
telemt_upstream_connect_attempt_total 456
telemt_upstream_connect_success_total 453
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 456
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 256
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 196
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 274
telemt_me_reconnect_success_total 271
telemt_me_reader_eof_total 245
telemt_me_idle_close_by_peer_total 245
telemt_me_route_drop_no_conn_total 249418
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 269322
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 806
telemt_desync_full_logged_total 265
telemt_desync_suppressed_total 541
telemt_desync_frames_bucket_total{bucket="1_2"} 150
telemt_desync_frames_bucket_total{bucket="3_10"} 338
telemt_desync_frames_bucket_total{bucket="gt_10"} 318
telemt_pool_swap_total 1
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 262
telemt_me_writer_restored_same_endpoint_total 241
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_user_connections_total{user="hello"} 269245
telemt_user_connections_current{user="hello"} 4621
telemt_user_octets_from_client{user="hello"} 5509969152 (5.13 GB)
telemt_user_octets_to_client{user="hello"} 71340563852 (66.44 GB)
telemt_user_unique_ips_current{user="hello"} 1447
telemt_user_unique_ips_recent_window{user="hello"} 590
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 2698.6 (0h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42136
telemt_connections_bad_total 7747
telemt_connections_current 602
telemt_connections_me_current 602
telemt_handshake_timeouts_total 463
telemt_upstream_connect_attempt_total 495
telemt_upstream_connect_success_total 490
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 255
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 234
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 334
telemt_me_reconnect_success_total 332
telemt_me_reader_eof_total 311
telemt_me_idle_close_by_peer_total 311
telemt_me_route_drop_no_conn_total 25271
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43447
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 169
telemt_desync_full_logged_total 51
telemt_desync_suppressed_total 118
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_pool_swap_total 1
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 333
telemt_me_writer_restored_same_endpoint_total 324
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 198
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 32360
telemt_user_connections_current{user="hello"} 602
telemt_user_octets_from_client{user="hello"} 287288052 (273.98 MB)
telemt_user_octets_to_client{user="hello"} 12433051924 (11.58 GB)
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 65145.0 (18h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2817689
telemt_connections_bad_total 181981
telemt_connections_current 4257
telemt_connections_me_current 4257
telemt_handshake_timeouts_total 50515
telemt_upstream_connect_attempt_total 11544
telemt_upstream_connect_success_total 11472
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 11544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6211
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 8282
telemt_me_reconnect_success_total 8228
telemt_me_reader_eof_total 8702
telemt_me_idle_close_by_peer_total 8702
telemt_me_route_drop_no_conn_total 960090
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2359664
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11815
telemt_desync_full_logged_total 3867
telemt_desync_suppressed_total 7948
telemt_desync_frames_bucket_total{bucket="1_2"} 2366
telemt_desync_frames_bucket_total{bucket="3_10"} 4159
telemt_desync_frames_bucket_total{bucket="gt_10"} 5290
telemt_pool_swap_total 67
telemt_me_writer_close_signal_drop_total 44
telemt_me_writer_removed_unexpected_total 8342
telemt_me_writer_restored_same_endpoint_total 8211
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 2358533
telemt_user_connections_current{user="hello"} 4257
telemt_user_octets_from_client{user="hello"} 52035282624 (48.46 GB)
telemt_user_octets_to_client{user="hello"} 1235531503612 (1.12 TB)
telemt_user_unique_ips_current{user="hello"} 1357
telemt_user_unique_ips_recent_window{user="hello"} 544
```