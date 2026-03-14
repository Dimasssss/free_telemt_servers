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

# Server Metrics 2026-03-14 04:19:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 161185.2 (44h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 625873
telemt_connections_bad_total 31423
telemt_handshake_timeouts_total 12944
telemt_upstream_connect_attempt_total 41228
telemt_upstream_connect_success_total 41019
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 41228
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18728
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22140
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5548
telemt_me_reconnect_attempts_total 37265
telemt_me_reconnect_success_total 32582
telemt_me_reader_eof_total 34815
telemt_me_idle_close_by_peer_total 34814
telemt_me_route_drop_no_conn_total 203224
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 529797
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1820
telemt_desync_full_logged_total 614
telemt_desync_suppressed_total 1206
telemt_desync_frames_bucket_total{bucket="1_2"} 386
telemt_desync_frames_bucket_total{bucket="3_10"} 672
telemt_desync_frames_bucket_total{bucket="gt_10"} 762
telemt_pool_swap_total 147
telemt_me_writer_removed_unexpected_total 33083
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 32562
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 501
telemt_user_connections_total{user="hello"} 529686
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 15742415094 (14.66 GB)
telemt_user_octets_to_client{user="hello"} 257837252532 (240.13 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 161078.2 (44h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 316415
telemt_connections_bad_total 2267
telemt_handshake_timeouts_total 2327
telemt_upstream_connect_attempt_total 146868
telemt_upstream_connect_success_total 145687
telemt_upstream_connect_fail_total 1181
telemt_upstream_connect_attempts_per_request{bucket="1"} 146868
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 108601
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34669
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2417
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1181
telemt_me_keepalive_timeout_total 3868
telemt_me_reconnect_attempts_total 169925
telemt_me_reconnect_success_total 34365
telemt_me_reader_eof_total 39499
telemt_me_idle_close_by_peer_total 39499
telemt_me_route_drop_no_conn_total 100398
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 196521
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 38930
telemt_me_refill_failed_total 4230
telemt_me_writer_restored_same_endpoint_total 34348
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4565
telemt_user_connections_total{user="hello"} 299634
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 3131931571 (2.92 GB)
telemt_user_octets_to_client{user="hello"} 96940993155 (90.28 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 161041.7 (44h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 368859
telemt_connections_bad_total 2922
telemt_handshake_timeouts_total 34796
telemt_upstream_connect_attempt_total 42689
telemt_upstream_connect_success_total 42680
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 42689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23113
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3390
telemt_me_reconnect_attempts_total 35906
telemt_me_reconnect_success_total 34626
telemt_me_reader_eof_total 37212
telemt_me_idle_close_by_peer_total 37212
telemt_me_route_drop_no_conn_total 131974
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 318361
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 151
telemt_me_writer_removed_unexpected_total 35047
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 34605
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 421
telemt_user_connections_total{user="hello"} 318151
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 12683553492 (11.81 GB)
telemt_user_octets_to_client{user="hello"} 128068966388 (119.27 GB)
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 161017.5 (44h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 470687
telemt_connections_bad_total 15548
telemt_handshake_timeouts_total 4408
telemt_upstream_connect_attempt_total 72373
telemt_upstream_connect_success_total 61865
telemt_upstream_connect_fail_total 10508
telemt_upstream_connect_attempts_per_request{bucket="1"} 72373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36910
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24614
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 332
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10508
telemt_me_keepalive_timeout_total 5280
telemt_me_reconnect_attempts_total 140869
telemt_me_reconnect_success_total 34822
telemt_me_reader_eof_total 39213
telemt_me_idle_close_by_peer_total 39205
telemt_me_route_drop_no_conn_total 168376
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 399423
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1710
telemt_desync_full_logged_total 503
telemt_desync_suppressed_total 1207
telemt_desync_frames_bucket_total{bucket="1_2"} 401
telemt_desync_frames_bucket_total{bucket="3_10"} 647
telemt_desync_frames_bucket_total{bucket="gt_10"} 662
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 38537
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 34812
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3715
telemt_user_connections_total{user="hello"} 418273
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 9195586043 (8.56 GB)
telemt_user_octets_to_client{user="hello"} 163177086880 (151.97 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 111189.0 (30h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183525
telemt_connections_bad_total 26481
telemt_handshake_timeouts_total 1640
telemt_upstream_connect_attempt_total 40116
telemt_upstream_connect_success_total 39745
telemt_upstream_connect_fail_total 371
telemt_upstream_connect_attempts_per_request{bucket="1"} 40116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20010
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19604
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 131
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 371
telemt_me_keepalive_timeout_total 2377
telemt_me_reconnect_attempts_total 42737
telemt_me_reconnect_success_total 29317
telemt_me_reader_eof_total 31374
telemt_me_idle_close_by_peer_total 31374
telemt_me_route_drop_no_conn_total 54256
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 145468
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 622
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 30001
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 29299
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 684
telemt_user_connections_total{user="hello"} 150221
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 2242532369 (2.09 GB)
telemt_user_octets_to_client{user="hello"} 68836019691 (64.11 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 160973.4 (44h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 916245
telemt_connections_bad_total 28173
telemt_handshake_timeouts_total 25485
telemt_upstream_connect_attempt_total 33465
telemt_upstream_connect_success_total 33286
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 33465
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17653
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_timeout_total 4579
telemt_me_reconnect_attempts_total 30003
telemt_me_reconnect_success_total 25332
telemt_me_reader_eof_total 27187
telemt_me_idle_close_by_peer_total 27184
telemt_me_route_drop_no_conn_total 436025
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 855497
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 760
telemt_desync_full_logged_total 250
telemt_desync_suppressed_total 510
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 151
telemt_me_writer_removed_unexpected_total 25801
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 25325
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 469
telemt_user_connections_total{user="hello"} 828161
telemt_user_connections_current{user="hello"} 285
telemt_user_octets_from_client{user="hello"} 14439510344 (13.45 GB)
telemt_user_octets_to_client{user="hello"} 417958438708 (389.25 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 33
```