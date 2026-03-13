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

# Server Metrics 2026-03-13 21:47:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 137655.3 (38h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 572965
telemt_connections_bad_total 16828
telemt_handshake_timeouts_total 12779
telemt_upstream_connect_attempt_total 34897
telemt_upstream_connect_success_total 34722
telemt_upstream_connect_fail_total 175
telemt_upstream_connect_attempts_per_request{bucket="1"} 34897
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18660
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 175
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5110
telemt_me_reconnect_attempts_total 32133
telemt_me_reconnect_success_total 27477
telemt_me_reader_eof_total 29334
telemt_me_idle_close_by_peer_total 29333
telemt_me_route_drop_no_conn_total 189007
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 492989
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1585
telemt_desync_full_logged_total 537
telemt_desync_suppressed_total 1048
telemt_desync_frames_bucket_total{bucket="1_2"} 340
telemt_desync_frames_bucket_total{bucket="3_10"} 591
telemt_desync_frames_bucket_total{bucket="gt_10"} 654
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 27930
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 27461
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 453
telemt_user_connections_total{user="hello"} 492884
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 14780284998 (13.77 GB)
telemt_user_octets_to_client{user="hello"} 242015702592 (225.39 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 137548.3 (38h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 291565
telemt_connections_bad_total 2138
telemt_handshake_timeouts_total 1918
telemt_upstream_connect_attempt_total 138509
telemt_upstream_connect_success_total 137503
telemt_upstream_connect_fail_total 1006
telemt_upstream_connect_attempts_per_request{bucket="1"} 138509
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105400
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29694
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2409
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1006
telemt_me_keepalive_timeout_total 3672
telemt_me_reconnect_attempts_total 144407
telemt_me_reconnect_success_total 27331
telemt_me_reader_eof_total 31731
telemt_me_idle_close_by_peer_total 31731
telemt_me_route_drop_no_conn_total 86449
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 173316
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 35
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
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 31243
telemt_me_refill_failed_total 3653
telemt_me_writer_restored_same_endpoint_total 27314
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3912
telemt_user_connections_total{user="hello"} 276429
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 2867390439 (2.67 GB)
telemt_user_octets_to_client{user="hello"} 84152146343 (78.37 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 137512.3 (38h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 339248
telemt_connections_bad_total 2658
telemt_handshake_timeouts_total 27118
telemt_upstream_connect_attempt_total 36582
telemt_upstream_connect_success_total 36577
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 36582
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19677
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2846
telemt_me_reconnect_attempts_total 30929
telemt_me_reconnect_success_total 29683
telemt_me_reader_eof_total 31841
telemt_me_idle_close_by_peer_total 31841
telemt_me_route_drop_no_conn_total 120885
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 297521
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
telemt_pool_swap_total 126
telemt_me_writer_removed_unexpected_total 30021
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 29663
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 338
telemt_user_connections_total{user="hello"} 297422
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 12327518180 (11.48 GB)
telemt_user_octets_to_client{user="hello"} 123586192736 (115.10 GB)
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 137487.6 (38h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 444138
telemt_connections_bad_total 15265
telemt_handshake_timeouts_total 4233
telemt_upstream_connect_attempt_total 64064
telemt_upstream_connect_success_total 53709
telemt_upstream_connect_fail_total 10355
telemt_upstream_connect_attempts_per_request{bucket="1"} 64064
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33501
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19896
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 303
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10355
telemt_me_keepalive_timeout_total 4769
telemt_me_reconnect_attempts_total 128916
telemt_me_reconnect_success_total 27825
telemt_me_reader_eof_total 31764
telemt_me_idle_close_by_peer_total 31757
telemt_me_route_drop_no_conn_total 154546
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 374739
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1589
telemt_desync_full_logged_total 470
telemt_desync_suppressed_total 1119
telemt_desync_frames_bucket_total{bucket="1_2"} 377
telemt_desync_frames_bucket_total{bucket="3_10"} 607
telemt_desync_frames_bucket_total{bucket="gt_10"} 605
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 31335
telemt_me_refill_failed_total 3153
telemt_me_writer_restored_same_endpoint_total 27815
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3510
telemt_user_connections_total{user="hello"} 393596
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 8918183115 (8.31 GB)
telemt_user_octets_to_client{user="hello"} 150031250624 (139.73 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 87659.2 (24h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148882
telemt_connections_bad_total 21972
telemt_handshake_timeouts_total 1536
telemt_upstream_connect_attempt_total 32745
telemt_upstream_connect_success_total 32435
telemt_upstream_connect_fail_total 310
telemt_upstream_connect_attempts_per_request{bucket="1"} 32745
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16667
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15657
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 310
telemt_me_keepalive_timeout_total 1296
telemt_me_reconnect_attempts_total 36553
telemt_me_reconnect_success_total 23156
telemt_me_reader_eof_total 24808
telemt_me_idle_close_by_peer_total 24808
telemt_me_route_drop_no_conn_total 45757
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 115822
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 611
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 468
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 302
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 23793
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 23138
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 637
telemt_user_connections_total{user="hello"} 120716
telemt_user_connections_current{user="hello"} 52
telemt_user_octets_from_client{user="hello"} 1400959197 (1.30 GB)
telemt_user_octets_to_client{user="hello"} 56886187283 (52.98 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 137443.7 (38h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 833347
telemt_connections_bad_total 27126
telemt_handshake_timeouts_total 25089
telemt_upstream_connect_attempt_total 28281
telemt_upstream_connect_success_total 28133
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 28281
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13142
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14952
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_keepalive_timeout_total 3120
telemt_me_reconnect_attempts_total 25975
telemt_me_reconnect_success_total 21324
telemt_me_reader_eof_total 22868
telemt_me_idle_close_by_peer_total 22865
telemt_me_route_drop_no_conn_total 396929
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 779799
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 693
telemt_desync_full_logged_total 226
telemt_desync_suppressed_total 467
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 128
telemt_me_writer_removed_unexpected_total 21752
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 21317
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 428
telemt_user_connections_total{user="hello"} 752660
telemt_user_connections_current{user="hello"} 315
telemt_user_octets_from_client{user="hello"} 13086214016 (12.19 GB)
telemt_user_octets_to_client{user="hello"} 375126574164 (349.36 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 36
```