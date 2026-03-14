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

# Server Metrics 2026-03-14 01:52:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 152322.9 (42h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 598959
telemt_connections_bad_total 22124
telemt_handshake_timeouts_total 12884
telemt_upstream_connect_attempt_total 38902
telemt_upstream_connect_success_total 38710
telemt_upstream_connect_fail_total 192
telemt_upstream_connect_attempts_per_request{bucket="1"} 38902
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17697
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20864
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 192
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5502
telemt_me_reconnect_attempts_total 35381
telemt_me_reconnect_success_total 30706
telemt_me_reader_eof_total 32807
telemt_me_idle_close_by_peer_total 32806
telemt_me_route_drop_no_conn_total 196392
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 512905
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1654
telemt_desync_full_logged_total 569
telemt_desync_suppressed_total 1085
telemt_desync_frames_bucket_total{bucket="1_2"} 355
telemt_desync_frames_bucket_total{bucket="3_10"} 623
telemt_desync_frames_bucket_total{bucket="gt_10"} 676
telemt_pool_swap_total 138
telemt_me_writer_removed_unexpected_total 31191
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 30690
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 485
telemt_user_connections_total{user="hello"} 512797
telemt_user_connections_current{user="hello"} 233
telemt_user_octets_from_client{user="hello"} 15584024354 (14.51 GB)
telemt_user_octets_to_client{user="hello"} 252726443144 (235.37 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 152215.9 (42h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 306882
telemt_connections_bad_total 2246
telemt_handshake_timeouts_total 1941
telemt_upstream_connect_attempt_total 143433
telemt_upstream_connect_success_total 142314
telemt_upstream_connect_fail_total 1119
telemt_upstream_connect_attempts_per_request{bucket="1"} 143433
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 107166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32733
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1119
telemt_me_keepalive_timeout_total 3806
telemt_me_reconnect_attempts_total 162334
telemt_me_reconnect_success_total 31387
telemt_me_reader_eof_total 36285
telemt_me_idle_close_by_peer_total 36285
telemt_me_route_drop_no_conn_total 96951
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 187823
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
telemt_me_writer_removed_unexpected_total 35773
telemt_me_refill_failed_total 4086
telemt_me_writer_restored_same_endpoint_total 31370
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4386
telemt_user_connections_total{user="hello"} 290935
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 3041632059 (2.83 GB)
telemt_user_octets_to_client{user="hello"} 91025076663 (84.77 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 152179.4 (42h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 359335
telemt_connections_bad_total 2824
telemt_handshake_timeouts_total 33223
telemt_upstream_connect_attempt_total 40389
telemt_upstream_connect_success_total 40383
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 40389
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18452
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21874
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3288
telemt_me_reconnect_attempts_total 34004
telemt_me_reconnect_success_total 32738
telemt_me_reader_eof_total 35172
telemt_me_idle_close_by_peer_total 35172
telemt_me_route_drop_no_conn_total 127854
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 310770
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
telemt_pool_swap_total 142
telemt_me_writer_removed_unexpected_total 33124
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 32718
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 386
telemt_user_connections_total{user="hello"} 310648
telemt_user_connections_current{user="hello"} 56
telemt_user_octets_from_client{user="hello"} 12614939168 (11.75 GB)
telemt_user_octets_to_client{user="hello"} 127025620272 (118.30 GB)
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 152155.2 (42h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 460857
telemt_connections_bad_total 15375
telemt_handshake_timeouts_total 4354
telemt_upstream_connect_attempt_total 69143
telemt_upstream_connect_success_total 58687
telemt_upstream_connect_fail_total 10456
telemt_upstream_connect_attempts_per_request{bucket="1"} 69143
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35475
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22880
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 323
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10456
telemt_me_keepalive_timeout_total 5090
telemt_me_reconnect_attempts_total 138106
telemt_me_reconnect_success_total 32068
telemt_me_reader_eof_total 36296
telemt_me_idle_close_by_peer_total 36288
telemt_me_route_drop_no_conn_total 162899
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 390623
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
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 35766
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 32058
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3698
telemt_user_connections_total{user="hello"} 409465
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 9076042727 (8.45 GB)
telemt_user_octets_to_client{user="hello"} 157824580440 (146.99 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 102326.7 (28h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 170759
telemt_connections_bad_total 24864
telemt_handshake_timeouts_total 1558
telemt_upstream_connect_attempt_total 37450
telemt_upstream_connect_success_total 37107
telemt_upstream_connect_fail_total 343
telemt_upstream_connect_attempts_per_request{bucket="1"} 37450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18851
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18134
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 122
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 343
telemt_me_keepalive_timeout_total 1391
telemt_me_reconnect_attempts_total 40531
telemt_me_reconnect_success_total 27116
telemt_me_reader_eof_total 29003
telemt_me_idle_close_by_peer_total 29003
telemt_me_route_drop_no_conn_total 50743
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 134543
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
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 27780
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 27098
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 664
telemt_user_connections_total{user="hello"} 139346
telemt_user_connections_current{user="hello"} 42
telemt_user_octets_from_client{user="hello"} 1920043009 (1.79 GB)
telemt_user_octets_to_client{user="hello"} 64697253855 (60.25 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 152111.2 (42h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 883944
telemt_connections_bad_total 27667
telemt_handshake_timeouts_total 25327
telemt_upstream_connect_attempt_total 31472
telemt_upstream_connect_success_total 31305
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 31472
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16619
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_timeout_total 3497
telemt_me_reconnect_attempts_total 28453
telemt_me_reconnect_success_total 23786
telemt_me_reader_eof_total 25484
telemt_me_idle_close_by_peer_total 25481
telemt_me_route_drop_no_conn_total 420974
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 826096
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 706
telemt_desync_full_logged_total 230
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 252
telemt_desync_frames_bucket_total{bucket="3_10"} 230
telemt_desync_frames_bucket_total{bucket="gt_10"} 224
telemt_pool_swap_total 141
telemt_me_writer_removed_unexpected_total 24241
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 23779
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 455
telemt_user_connections_total{user="hello"} 798852
telemt_user_connections_current{user="hello"} 243
telemt_user_octets_from_client{user="hello"} 14164390232 (13.19 GB)
telemt_user_octets_to_client{user="hello"} 407126126460 (379.17 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 35
```