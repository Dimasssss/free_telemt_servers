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

# Server Metrics 2026-03-17 15:40:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 75329.2 (20h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 835384
telemt_connections_bad_total 6250
telemt_handshake_timeouts_total 24246
telemt_upstream_connect_attempt_total 17925
telemt_upstream_connect_success_total 17454
telemt_upstream_connect_fail_total 471
telemt_upstream_connect_attempts_per_request{bucket="1"} 17925
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8132
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 471
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 169
telemt_me_reconnect_attempts_total 26086
telemt_me_reconnect_success_total 11377
telemt_me_reader_eof_total 12386
telemt_me_idle_close_by_peer_total 12385
telemt_me_route_drop_no_conn_total 350395
telemt_me_route_drop_channel_closed_total 85
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 759510
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5253
telemt_desync_full_logged_total 1459
telemt_desync_suppressed_total 3794
telemt_desync_frames_bucket_total{bucket="1_2"} 1508
telemt_desync_frames_bucket_total{bucket="3_10"} 2070
telemt_desync_frames_bucket_total{bucket="gt_10"} 1675
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 11990
telemt_me_refill_failed_total 454
telemt_me_writer_restored_same_endpoint_total 11355
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 613
telemt_user_connections_total{user="hello"} 761337
telemt_user_connections_current{user="hello"} 922
telemt_user_octets_from_client{user="hello"} 12169877567 (11.33 GB)
telemt_user_octets_to_client{user="hello"} 250982932971 (233.75 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 319
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 75580.7 (20h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 551691
telemt_connections_bad_total 31859
telemt_handshake_timeouts_total 28384
telemt_upstream_connect_attempt_total 113544
telemt_upstream_connect_success_total 112996
telemt_upstream_connect_fail_total 548
telemt_upstream_connect_attempts_per_request{bucket="1"} 113544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 91195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13497
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8302
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 548
telemt_me_keepalive_timeout_total 330
telemt_me_reconnect_attempts_total 40117
telemt_me_reconnect_success_total 13482
telemt_me_reader_eof_total 14869
telemt_me_idle_close_by_peer_total 14869
telemt_me_route_drop_no_conn_total 194201
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 370594
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1479
telemt_desync_full_logged_total 465
telemt_desync_suppressed_total 1014
telemt_desync_frames_bucket_total{bucket="1_2"} 334
telemt_desync_frames_bucket_total{bucket="3_10"} 647
telemt_desync_frames_bucket_total{bucket="gt_10"} 498
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14477
telemt_me_refill_failed_total 828
telemt_me_writer_restored_same_endpoint_total 13466
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 995
telemt_user_connections_total{user="hello"} 466230
telemt_user_connections_current{user="hello"} 806
telemt_user_octets_from_client{user="hello"} 5183632278 (4.83 GB)
telemt_user_octets_to_client{user="hello"} 132900335100 (123.77 GB)
telemt_user_msgs_from_client{user="hello"} 1395588
telemt_user_msgs_to_client{user="hello"} 5021192
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 75356.3 (20h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 280799
telemt_connections_bad_total 7843
telemt_handshake_timeouts_total 18638
telemt_upstream_connect_attempt_total 19596
telemt_upstream_connect_success_total 19493
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 19596
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10629
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 30802
telemt_me_reconnect_success_total 15667
telemt_me_reader_eof_total 17005
telemt_me_idle_close_by_peer_total 17002
telemt_me_route_drop_no_conn_total 132134
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 240005
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 811
telemt_desync_full_logged_total 235
telemt_desync_suppressed_total 576
telemt_desync_frames_bucket_total{bucket="1_2"} 294
telemt_desync_frames_bucket_total{bucket="3_10"} 365
telemt_desync_frames_bucket_total{bucket="gt_10"} 152
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 16350
telemt_me_refill_failed_total 470
telemt_me_writer_restored_same_endpoint_total 15656
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 683
telemt_user_connections_total{user="hello"} 239858
telemt_user_connections_current{user="hello"} 323
telemt_user_octets_from_client{user="hello"} 18608310408 (17.33 GB)
telemt_user_octets_to_client{user="hello"} 58504415996 (54.49 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 75415.8 (20h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 657374
telemt_connections_bad_total 8779
telemt_handshake_timeouts_total 13894
telemt_upstream_connect_attempt_total 42315
telemt_upstream_connect_success_total 42048
telemt_upstream_connect_fail_total 267
telemt_upstream_connect_attempts_per_request{bucket="1"} 42315
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32786
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9068
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 181
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 267
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 29496
telemt_me_reconnect_success_total 11961
telemt_me_reader_eof_total 13158
telemt_me_idle_close_by_peer_total 13157
telemt_me_route_drop_no_conn_total 253862
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 541741
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1864
telemt_desync_full_logged_total 630
telemt_desync_suppressed_total 1234
telemt_desync_frames_bucket_total{bucket="1_2"} 471
telemt_desync_frames_bucket_total{bucket="3_10"} 836
telemt_desync_frames_bucket_total{bucket="gt_10"} 557
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12717
telemt_me_refill_failed_total 543
telemt_me_writer_restored_same_endpoint_total 11952
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 756
telemt_user_connections_total{user="hello"} 567821
telemt_user_connections_current{user="hello"} 843
telemt_user_octets_from_client{user="hello"} 6837598193 (6.37 GB)
telemt_user_octets_to_client{user="hello"} 171786804159 (159.99 GB)
telemt_user_msgs_from_client{user="hello"} 244919
telemt_user_msgs_to_client{user="hello"} 1339743
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 75387.7 (20h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 300270
telemt_connections_bad_total 57701
telemt_handshake_timeouts_total 3725
telemt_upstream_connect_attempt_total 21556
telemt_upstream_connect_success_total 21081
telemt_upstream_connect_fail_total 475
telemt_upstream_connect_attempts_per_request{bucket="1"} 21556
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9459
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11329
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 293
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 475
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 44122
telemt_me_reconnect_success_total 16898
telemt_me_reader_eof_total 18338
telemt_me_idle_close_by_peer_total 18336
telemt_me_route_drop_no_conn_total 85473
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 226194
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 10
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
telemt_me_writer_removed_unexpected_total 18028
telemt_me_refill_failed_total 846
telemt_me_writer_restored_same_endpoint_total 16890
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1130
telemt_user_connections_total{user="hello"} 226717
telemt_user_connections_current{user="hello"} 292
telemt_user_octets_from_client{user="hello"} 2807610207 (2.61 GB)
telemt_user_octets_to_client{user="hello"} 84021541227 (78.25 GB)
telemt_user_msgs_from_client{user="hello"} 1159
telemt_user_msgs_to_client{user="hello"} 2341
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 75549.7 (20h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 732251
telemt_connections_bad_total 59675
telemt_handshake_timeouts_total 7080
telemt_upstream_connect_attempt_total 15230
telemt_upstream_connect_success_total 15148
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 15230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7384
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7739
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 21661
telemt_me_reconnect_success_total 11364
telemt_me_reader_eof_total 12356
telemt_me_idle_close_by_peer_total 12356
telemt_me_route_drop_no_conn_total 535531
telemt_me_route_drop_channel_closed_total 51
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 743539
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1093
telemt_desync_full_logged_total 389
telemt_desync_suppressed_total 704
telemt_desync_frames_bucket_total{bucket="1_2"} 258
telemt_desync_frames_bucket_total{bucket="3_10"} 439
telemt_desync_frames_bucket_total{bucket="gt_10"} 396
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 11863
telemt_me_refill_failed_total 319
telemt_me_writer_restored_same_endpoint_total 11350
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 499
telemt_user_connections_total{user="hello"} 628636
telemt_user_connections_current{user="hello"} 900
telemt_user_octets_from_client{user="hello"} 9227312772 (8.59 GB)
telemt_user_octets_to_client{user="hello"} 280638583404 (261.37 GB)
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 23315.8 (6h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18043
telemt_connections_bad_total 81
telemt_handshake_timeouts_total 313
telemt_upstream_connect_attempt_total 12488
telemt_upstream_connect_success_total 12382
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 12488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5635
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 22607
telemt_me_reconnect_success_total 11040
telemt_me_reader_eof_total 11689
telemt_me_idle_close_by_peer_total 11689
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 6779
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17184
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 11525
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 11024
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 485
telemt_user_connections_total{user="hello"} 17281
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 548136189 (522.74 MB)
telemt_user_octets_to_client{user="hello"} 24063003946 (22.41 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 7
```