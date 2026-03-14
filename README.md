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

# Server Metrics 2026-03-14 00:30:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 147435.1 (40h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 590347
telemt_connections_bad_total 20737
telemt_handshake_timeouts_total 12845
telemt_upstream_connect_attempt_total 37518
telemt_upstream_connect_success_total 37330
telemt_upstream_connect_fail_total 188
telemt_upstream_connect_attempts_per_request{bucket="1"} 37518
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17051
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20131
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 188
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5167
telemt_me_reconnect_attempts_total 34265
telemt_me_reconnect_success_total 29594
telemt_me_reader_eof_total 31626
telemt_me_idle_close_by_peer_total 31625
telemt_me_route_drop_no_conn_total 194198
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 505890
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1635
telemt_desync_full_logged_total 558
telemt_desync_suppressed_total 1077
telemt_desync_frames_bucket_total{bucket="1_2"} 352
telemt_desync_frames_bucket_total{bucket="3_10"} 613
telemt_desync_frames_bucket_total{bucket="gt_10"} 670
telemt_pool_swap_total 133
telemt_me_writer_removed_unexpected_total 30068
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 29578
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 474
telemt_user_connections_total{user="hello"} 505785
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 15451350758 (14.39 GB)
telemt_user_octets_to_client{user="hello"} 250328963632 (233.14 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 147327.9 (40h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 303358
telemt_connections_bad_total 2232
telemt_handshake_timeouts_total 1932
telemt_upstream_connect_attempt_total 142201
telemt_upstream_connect_success_total 141113
telemt_upstream_connect_fail_total 1088
telemt_upstream_connect_attempts_per_request{bucket="1"} 142201
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106637
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32061
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1088
telemt_me_keepalive_timeout_total 3770
telemt_me_reconnect_attempts_total 157328
telemt_me_reconnect_success_total 30448
telemt_me_reader_eof_total 35203
telemt_me_idle_close_by_peer_total 35203
telemt_me_route_drop_no_conn_total 93559
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 184485
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 38
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
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 34698
telemt_me_refill_failed_total 3959
telemt_me_writer_restored_same_endpoint_total 30431
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4250
telemt_user_connections_total{user="hello"} 287597
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 3014167759 (2.81 GB)
telemt_user_octets_to_client{user="hello"} 89694242515 (83.53 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 147291.8 (40h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 354793
telemt_connections_bad_total 2769
telemt_handshake_timeouts_total 33205
telemt_upstream_connect_attempt_total 39075
telemt_upstream_connect_success_total 39069
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 39075
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17901
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21113
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2955
telemt_me_reconnect_attempts_total 32943
telemt_me_reconnect_success_total 31684
telemt_me_reader_eof_total 34035
telemt_me_idle_close_by_peer_total 34035
telemt_me_route_drop_no_conn_total 125538
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 306415
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
telemt_pool_swap_total 137
telemt_me_writer_removed_unexpected_total 32059
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 31664
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 375
telemt_user_connections_total{user="hello"} 306317
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 12572836844 (11.71 GB)
telemt_user_octets_to_client{user="hello"} 126264106320 (117.59 GB)
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 147267.1 (40h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 455905
telemt_connections_bad_total 15364
telemt_handshake_timeouts_total 4319
telemt_upstream_connect_attempt_total 67267
telemt_upstream_connect_success_total 56841
telemt_upstream_connect_fail_total 10426
telemt_upstream_connect_attempts_per_request{bucket="1"} 67267
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34736
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21780
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 316
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10426
telemt_me_keepalive_timeout_total 5047
telemt_me_reconnect_attempts_total 135440
telemt_me_reconnect_success_total 30465
telemt_me_reader_eof_total 34617
telemt_me_idle_close_by_peer_total 34609
telemt_me_route_drop_no_conn_total 160260
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 385941
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1692
telemt_desync_full_logged_total 497
telemt_desync_suppressed_total 1195
telemt_desync_frames_bucket_total{bucket="1_2"} 396
telemt_desync_frames_bucket_total{bucket="3_10"} 644
telemt_desync_frames_bucket_total{bucket="gt_10"} 652
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 34114
telemt_me_refill_failed_total 3274
telemt_me_writer_restored_same_endpoint_total 30455
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3649
telemt_user_connections_total{user="hello"} 404783
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 9044126603 (8.42 GB)
telemt_user_octets_to_client{user="hello"} 154897516412 (144.26 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 97439.2 (27h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 163326
telemt_connections_bad_total 23939
telemt_handshake_timeouts_total 1551
telemt_upstream_connect_attempt_total 35907
telemt_upstream_connect_success_total 35580
telemt_upstream_connect_fail_total 327
telemt_upstream_connect_attempts_per_request{bucket="1"} 35907
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17268
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 327
telemt_me_keepalive_timeout_total 1356
telemt_me_reconnect_attempts_total 39220
telemt_me_reconnect_success_total 25808
telemt_me_reader_eof_total 27610
telemt_me_idle_close_by_peer_total 27610
telemt_me_route_drop_no_conn_total 48877
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 128118
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
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 26464
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 25790
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 656
telemt_user_connections_total{user="hello"} 132955
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 1712976561 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 63559721471 (59.19 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 147223.2 (40h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 868305
telemt_connections_bad_total 27374
telemt_handshake_timeouts_total 25275
telemt_upstream_connect_attempt_total 30371
telemt_upstream_connect_success_total 30207
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 30371
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14094
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16072
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_timeout_total 3408
telemt_me_reconnect_attempts_total 27573
telemt_me_reconnect_success_total 22908
telemt_me_reader_eof_total 24552
telemt_me_idle_close_by_peer_total 24549
telemt_me_route_drop_no_conn_total 413815
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 811086
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 702
telemt_desync_full_logged_total 229
telemt_desync_suppressed_total 473
telemt_desync_frames_bucket_total{bucket="1_2"} 252
telemt_desync_frames_bucket_total{bucket="3_10"} 229
telemt_desync_frames_bucket_total{bucket="gt_10"} 221
telemt_pool_swap_total 137
telemt_me_writer_removed_unexpected_total 23353
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 22901
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 445
telemt_user_connections_total{user="hello"} 783851
telemt_user_connections_current{user="hello"} 281
telemt_user_octets_from_client{user="hello"} 14040024592 (13.08 GB)
telemt_user_octets_to_client{user="hello"} 400282647992 (372.79 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 39
```