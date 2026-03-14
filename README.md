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

# Server Metrics 2026-03-14 02:17:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 153850.4 (42h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 601820
telemt_connections_bad_total 22445
telemt_handshake_timeouts_total 12901
telemt_upstream_connect_attempt_total 39252
telemt_upstream_connect_success_total 39059
telemt_upstream_connect_fail_total 193
telemt_upstream_connect_attempts_per_request{bucket="1"} 39252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17875
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21035
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 193
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5505
telemt_me_reconnect_attempts_total 35687
telemt_me_reconnect_success_total 31010
telemt_me_reader_eof_total 33123
telemt_me_idle_close_by_peer_total 33122
telemt_me_route_drop_no_conn_total 197437
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 515322
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1666
telemt_desync_full_logged_total 574
telemt_desync_suppressed_total 1092
telemt_desync_frames_bucket_total{bucket="1_2"} 356
telemt_desync_frames_bucket_total{bucket="3_10"} 629
telemt_desync_frames_bucket_total{bucket="gt_10"} 681
telemt_pool_swap_total 139
telemt_me_writer_removed_unexpected_total 31497
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 30994
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 487
telemt_user_connections_total{user="hello"} 515213
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 15605992266 (14.53 GB)
telemt_user_octets_to_client{user="hello"} 253375853244 (235.97 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 153743.4 (42h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 308339
telemt_connections_bad_total 2247
telemt_handshake_timeouts_total 1941
telemt_upstream_connect_attempt_total 143900
telemt_upstream_connect_success_total 142775
telemt_upstream_connect_fail_total 1125
telemt_upstream_connect_attempts_per_request{bucket="1"} 143900
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 107383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32977
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1125
telemt_me_keepalive_timeout_total 3809
telemt_me_reconnect_attempts_total 162752
telemt_me_reconnect_success_total 31803
telemt_me_reader_eof_total 36723
telemt_me_idle_close_by_peer_total 36723
telemt_me_route_drop_no_conn_total 97596
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 189236
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 39
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
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 36190
telemt_me_refill_failed_total 4086
telemt_me_writer_restored_same_endpoint_total 31786
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4387
telemt_user_connections_total{user="hello"} 292348
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 3049896579 (2.84 GB)
telemt_user_octets_to_client{user="hello"} 91372448935 (85.10 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 153706.9 (42h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 360622
telemt_connections_bad_total 2825
telemt_handshake_timeouts_total 33240
telemt_upstream_connect_attempt_total 40786
telemt_upstream_connect_success_total 40780
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 40786
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22090
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3294
telemt_me_reconnect_attempts_total 34350
telemt_me_reconnect_success_total 33082
telemt_me_reader_eof_total 35551
telemt_me_idle_close_by_peer_total 35551
telemt_me_route_drop_no_conn_total 128632
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 312031
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
telemt_pool_swap_total 144
telemt_me_writer_removed_unexpected_total 33473
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 33062
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 391
telemt_user_connections_total{user="hello"} 311861
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 12620092220 (11.75 GB)
telemt_user_octets_to_client{user="hello"} 127153088784 (118.42 GB)
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 153682.7 (42h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 462114
telemt_connections_bad_total 15376
telemt_handshake_timeouts_total 4358
telemt_upstream_connect_attempt_total 69714
telemt_upstream_connect_success_total 59248
telemt_upstream_connect_fail_total 10466
telemt_upstream_connect_attempts_per_request{bucket="1"} 69714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35720
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23195
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 324
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10466
telemt_me_keepalive_timeout_total 5099
telemt_me_reconnect_attempts_total 138599
telemt_me_reconnect_success_total 32558
telemt_me_reader_eof_total 36817
telemt_me_idle_close_by_peer_total 36809
telemt_me_route_drop_no_conn_total 163476
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 391828
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1708
telemt_desync_full_logged_total 501
telemt_desync_suppressed_total 1207
telemt_desync_frames_bucket_total{bucket="1_2"} 400
telemt_desync_frames_bucket_total{bucket="3_10"} 646
telemt_desync_frames_bucket_total{bucket="gt_10"} 662
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 36259
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 32548
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3701
telemt_user_connections_total{user="hello"} 410661
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 9081977519 (8.46 GB)
telemt_user_octets_to_client{user="hello"} 158490019904 (147.61 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 103854.4 (28h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173540
telemt_connections_bad_total 25140
telemt_handshake_timeouts_total 1564
telemt_upstream_connect_attempt_total 37917
telemt_upstream_connect_success_total 37569
telemt_upstream_connect_fail_total 348
telemt_upstream_connect_attempts_per_request{bucket="1"} 37917
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19059
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18387
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 123
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 348
telemt_me_keepalive_timeout_total 1402
telemt_me_reconnect_attempts_total 40906
telemt_me_reconnect_success_total 27490
telemt_me_reader_eof_total 29414
telemt_me_idle_close_by_peer_total 29414
telemt_me_route_drop_no_conn_total 51557
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 137042
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 619
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 474
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 28158
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 27472
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 668
telemt_user_connections_total{user="hello"} 141822
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 1985312353 (1.85 GB)
telemt_user_octets_to_client{user="hello"} 64918458959 (60.46 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 153638.8 (42h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 888524
telemt_connections_bad_total 27715
telemt_handshake_timeouts_total 25332
telemt_upstream_connect_attempt_total 31818
telemt_upstream_connect_success_total 31649
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 31818
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16790
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_keepalive_timeout_total 3497
telemt_me_reconnect_attempts_total 28711
telemt_me_reconnect_success_total 24044
telemt_me_reader_eof_total 25765
telemt_me_idle_close_by_peer_total 25762
telemt_me_route_drop_no_conn_total 423544
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 830522
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 708
telemt_desync_full_logged_total 231
telemt_desync_suppressed_total 477
telemt_desync_frames_bucket_total{bucket="1_2"} 253
telemt_desync_frames_bucket_total{bucket="3_10"} 231
telemt_desync_frames_bucket_total{bucket="gt_10"} 224
telemt_pool_swap_total 143
telemt_me_writer_removed_unexpected_total 24503
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 24037
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 459
telemt_user_connections_total{user="hello"} 803279
telemt_user_connections_current{user="hello"} 238
telemt_user_octets_from_client{user="hello"} 14250915196 (13.27 GB)
telemt_user_octets_to_client{user="hello"} 409170993092 (381.07 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 30
```