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

# Server Metrics 2026-03-13 18:03:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 124210.7 (34h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 524620
telemt_connections_bad_total 8903
telemt_handshake_timeouts_total 12081
telemt_upstream_connect_attempt_total 31115
telemt_upstream_connect_success_total 30964
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 31115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14048
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16829
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3445
telemt_me_reconnect_attempts_total 29408
telemt_me_reconnect_success_total 24767
telemt_me_reader_eof_total 26461
telemt_me_idle_close_by_peer_total 26460
telemt_me_route_drop_no_conn_total 171285
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 455633
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1465
telemt_desync_full_logged_total 507
telemt_desync_suppressed_total 958
telemt_desync_frames_bucket_total{bucket="1_2"} 322
telemt_desync_frames_bucket_total{bucket="3_10"} 536
telemt_desync_frames_bucket_total{bucket="gt_10"} 607
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 25186
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 24751
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 419
telemt_user_connections_total{user="hello"} 455201
telemt_user_connections_current{user="hello"} 289
telemt_user_octets_from_client{user="hello"} 8391880008 (7.82 GB)
telemt_user_octets_to_client{user="hello"} 214560301892 (199.82 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 124104.7 (34h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 258881
telemt_connections_bad_total 1951
telemt_handshake_timeouts_total 1833
telemt_upstream_connect_attempt_total 112250
telemt_upstream_connect_success_total 111405
telemt_upstream_connect_fail_total 845
telemt_upstream_connect_attempts_per_request{bucket="1"} 112250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 83274
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1613
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 845
telemt_me_keepalive_timeout_total 1518
telemt_me_reconnect_attempts_total 127328
telemt_me_reconnect_success_total 26033
telemt_me_reader_eof_total 29952
telemt_me_idle_close_by_peer_total 29952
telemt_me_route_drop_no_conn_total 82825
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 166175
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 30
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
telemt_me_writer_removed_unexpected_total 29422
telemt_me_refill_failed_total 3161
telemt_me_writer_restored_same_endpoint_total 26016
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3389
telemt_user_connections_total{user="hello"} 245152
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 2559566572 (2.38 GB)
telemt_user_octets_to_client{user="hello"} 75296939050 (70.13 GB)
telemt_user_msgs_from_client{user="hello"} 1242308
telemt_user_msgs_to_client{user="hello"} 7218215
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 124068.3 (34h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 305659
telemt_connections_bad_total 2532
telemt_handshake_timeouts_total 17830
telemt_upstream_connect_attempt_total 33077
telemt_upstream_connect_success_total 33073
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 33077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17699
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2664
telemt_me_reconnect_attempts_total 28073
telemt_me_reconnect_success_total 26844
telemt_me_reader_eof_total 28781
telemt_me_idle_close_by_peer_total 28781
telemt_me_route_drop_no_conn_total 109148
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 274580
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 104
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 113
telemt_me_writer_removed_unexpected_total 27143
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 26824
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 299
telemt_user_connections_total{user="hello"} 274491
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 10241279712 (9.54 GB)
telemt_user_octets_to_client{user="hello"} 112749956232 (105.01 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 124043.6 (34h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 411980
telemt_connections_bad_total 15110
telemt_handshake_timeouts_total 3878
telemt_upstream_connect_attempt_total 60395
telemt_upstream_connect_success_total 50143
telemt_upstream_connect_fail_total 10252
telemt_upstream_connect_attempts_per_request{bucket="1"} 60395
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18006
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 285
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10252
telemt_me_keepalive_timeout_total 4661
telemt_me_reconnect_attempts_total 114581
telemt_me_reconnect_success_total 24925
telemt_me_reader_eof_total 28430
telemt_me_idle_close_by_peer_total 28423
telemt_me_route_drop_no_conn_total 142021
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 344027
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1353
telemt_desync_full_logged_total 403
telemt_desync_suppressed_total 950
telemt_desync_frames_bucket_total{bucket="1_2"} 333
telemt_desync_frames_bucket_total{bucket="3_10"} 521
telemt_desync_frames_bucket_total{bucket="gt_10"} 499
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 28041
telemt_me_refill_failed_total 2796
telemt_me_writer_restored_same_endpoint_total 24915
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3116
telemt_user_connections_total{user="hello"} 362917
telemt_user_connections_current{user="hello"} 198
telemt_user_octets_from_client{user="hello"} 8379493579 (7.80 GB)
telemt_user_octets_to_client{user="hello"} 129630775564 (120.73 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 74215.2 (20h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122114
telemt_connections_bad_total 15386
telemt_handshake_timeouts_total 1396
telemt_upstream_connect_attempt_total 29216
telemt_upstream_connect_success_total 28946
telemt_upstream_connect_fail_total 270
telemt_upstream_connect_attempts_per_request{bucket="1"} 29216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13890
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 270
telemt_me_keepalive_timeout_total 1181
telemt_me_reconnect_attempts_total 33712
telemt_me_reconnect_success_total 20324
telemt_me_reader_eof_total 21798
telemt_me_idle_close_by_peer_total 21798
telemt_me_route_drop_no_conn_total 38360
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 96512
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 471
telemt_desync_full_logged_total 97
telemt_desync_suppressed_total 374
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 253
telemt_desync_frames_bucket_total{bucket="gt_10"} 155
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 20927
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 20306
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 603
telemt_user_connections_total{user="hello"} 101409
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 1201335029 (1.12 GB)
telemt_user_octets_to_client{user="hello"} 33903402927 (31.58 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 124000.3 (34h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 758057
telemt_connections_bad_total 24762
telemt_handshake_timeouts_total 24484
telemt_upstream_connect_attempt_total 25772
telemt_upstream_connect_success_total 25635
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 25772
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12017
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13586
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_timeout_total 2984
telemt_me_reconnect_attempts_total 24128
telemt_me_reconnect_success_total 19485
telemt_me_reader_eof_total 20911
telemt_me_idle_close_by_peer_total 20908
telemt_me_route_drop_no_conn_total 359386
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 711250
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 680
telemt_desync_full_logged_total 220
telemt_desync_suppressed_total 460
telemt_desync_frames_bucket_total{bucket="1_2"} 241
telemt_desync_frames_bucket_total{bucket="3_10"} 223
telemt_desync_frames_bucket_total{bucket="gt_10"} 216
telemt_pool_swap_total 114
telemt_me_writer_removed_unexpected_total 19886
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 19478
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 401
telemt_user_connections_total{user="hello"} 684137
telemt_user_connections_current{user="hello"} 454
telemt_user_octets_from_client{user="hello"} 11995275688 (11.17 GB)
telemt_user_octets_to_client{user="hello"} 340861888224 (317.45 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 45
```