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

# Server Metrics 2026-03-13 19:55:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 130934.1 (36h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 554395
telemt_connections_bad_total 14028
telemt_handshake_timeouts_total 12524
telemt_upstream_connect_attempt_total 33184
telemt_upstream_connect_success_total 33016
telemt_upstream_connect_fail_total 168
telemt_upstream_connect_attempts_per_request{bucket="1"} 33184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17680
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 168
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5048
telemt_me_reconnect_attempts_total 30731
telemt_me_reconnect_success_total 26080
telemt_me_reader_eof_total 27848
telemt_me_idle_close_by_peer_total 27847
telemt_me_route_drop_no_conn_total 183370
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 478350
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1535
telemt_desync_full_logged_total 523
telemt_desync_suppressed_total 1012
telemt_desync_frames_bucket_total{bucket="1_2"} 333
telemt_desync_frames_bucket_total{bucket="3_10"} 564
telemt_desync_frames_bucket_total{bucket="gt_10"} 638
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 26518
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 26064
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 438
telemt_user_connections_total{user="hello"} 478245
telemt_user_connections_current{user="hello"} 282
telemt_user_octets_from_client{user="hello"} 8827242450 (8.22 GB)
telemt_user_octets_to_client{user="hello"} 228839977460 (213.12 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 130827.8 (36h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 278763
telemt_connections_bad_total 2098
telemt_handshake_timeouts_total 1875
telemt_upstream_connect_attempt_total 129601
telemt_upstream_connect_success_total 128650
telemt_upstream_connect_fail_total 951
telemt_upstream_connect_attempts_per_request{bucket="1"} 129601
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 97996
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28345
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2309
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 951
telemt_me_keepalive_timeout_total 3616
telemt_me_reconnect_attempts_total 137956
telemt_me_reconnect_success_total 26358
telemt_me_reader_eof_total 30582
telemt_me_idle_close_by_peer_total 30582
telemt_me_route_drop_no_conn_total 83772
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168733
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 30090
telemt_me_refill_failed_total 3482
telemt_me_writer_restored_same_endpoint_total 26341
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3732
telemt_user_connections_total{user="hello"} 264275
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 2721838172 (2.53 GB)
telemt_user_octets_to_client{user="hello"} 79462190850 (74.00 GB)
telemt_user_msgs_from_client{user="hello"} 1529824
telemt_user_msgs_to_client{user="hello"} 8392285
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 130791.5 (36h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 325171
telemt_connections_bad_total 2636
telemt_handshake_timeouts_total 22770
telemt_upstream_connect_attempt_total 34709
telemt_upstream_connect_success_total 34704
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 34709
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16059
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18604
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2799
telemt_me_reconnect_attempts_total 29360
telemt_me_reconnect_success_total 28122
telemt_me_reader_eof_total 30174
telemt_me_idle_close_by_peer_total 30174
telemt_me_route_drop_no_conn_total 116268
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 288440
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
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
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 28440
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 28102
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 318
telemt_user_connections_total{user="hello"} 288351
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 11799431416 (10.99 GB)
telemt_user_octets_to_client{user="hello"} 120536699644 (112.26 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 130767.0 (36h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 429991
telemt_connections_bad_total 15228
telemt_handshake_timeouts_total 4157
telemt_upstream_connect_attempt_total 62799
telemt_upstream_connect_success_total 52502
telemt_upstream_connect_fail_total 10297
telemt_upstream_connect_attempts_per_request{bucket="1"} 62799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32841
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19355
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 297
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10297
telemt_me_keepalive_timeout_total 4750
telemt_me_reconnect_attempts_total 118771
telemt_me_reconnect_success_total 26932
telemt_me_reader_eof_total 30571
telemt_me_idle_close_by_peer_total 30564
telemt_me_route_drop_no_conn_total 149116
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 361152
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1469
telemt_desync_full_logged_total 438
telemt_desync_suppressed_total 1031
telemt_desync_frames_bucket_total{bucket="1_2"} 354
telemt_desync_frames_bucket_total{bucket="3_10"} 557
telemt_desync_frames_bucket_total{bucket="gt_10"} 558
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 30141
telemt_me_refill_failed_total 2864
telemt_me_writer_restored_same_endpoint_total 26922
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3209
telemt_user_connections_total{user="hello"} 380017
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 8607035891 (8.02 GB)
telemt_user_octets_to_client{user="hello"} 137468262864 (128.03 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 80938.5 (22h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137686
telemt_connections_bad_total 17475
telemt_handshake_timeouts_total 1427
telemt_upstream_connect_attempt_total 30908
telemt_upstream_connect_success_total 30614
telemt_upstream_connect_fail_total 294
telemt_upstream_connect_attempts_per_request{bucket="1"} 30908
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15793
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14719
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 294
telemt_me_keepalive_timeout_total 1254
telemt_me_reconnect_attempts_total 35076
telemt_me_reconnect_success_total 21685
telemt_me_reader_eof_total 23233
telemt_me_idle_close_by_peer_total 23233
telemt_me_route_drop_no_conn_total 43034
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109453
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 604
telemt_desync_full_logged_total 140
telemt_desync_suppressed_total 464
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 302
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 22302
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 21667
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 617
telemt_user_connections_total{user="hello"} 114347
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 1330496329 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 49617093871 (46.21 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 130723.1 (36h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 801068
telemt_connections_bad_total 24805
telemt_handshake_timeouts_total 24902
telemt_upstream_connect_attempt_total 26973
telemt_upstream_connect_success_total 26830
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 26973
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14251
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 3071
telemt_me_reconnect_attempts_total 24976
telemt_me_reconnect_success_total 20329
telemt_me_reader_eof_total 21808
telemt_me_idle_close_by_peer_total 21805
telemt_me_route_drop_no_conn_total 381222
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 751189
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 691
telemt_desync_full_logged_total 225
telemt_desync_suppressed_total 466
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 20747
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 20322
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 418
telemt_user_connections_total{user="hello"} 724050
telemt_user_connections_current{user="hello"} 532
telemt_user_octets_from_client{user="hello"} 12555548796 (11.69 GB)
telemt_user_octets_to_client{user="hello"} 355372270548 (330.97 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 62
```