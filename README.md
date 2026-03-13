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

# Server Metrics 2026-03-13 12:32:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 104340.1 (28h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 426114
telemt_connections_bad_total 3210
telemt_handshake_timeouts_total 8380
telemt_upstream_connect_attempt_total 26498
telemt_upstream_connect_success_total 26373
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 26498
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11897
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14428
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2395
telemt_me_reconnect_attempts_total 24680
telemt_me_reconnect_success_total 21155
telemt_me_reader_eof_total 22582
telemt_me_idle_close_by_peer_total 22581
telemt_me_route_drop_no_conn_total 134989
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 370258
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1243
telemt_desync_full_logged_total 442
telemt_desync_suppressed_total 801
telemt_desync_frames_bucket_total{bucket="1_2"} 250
telemt_desync_frames_bucket_total{bucket="3_10"} 459
telemt_desync_frames_bucket_total{bucket="gt_10"} 534
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 21484
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 21139
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 329
telemt_user_connections_total{user="hello"} 369850
telemt_user_connections_current{user="hello"} 392
telemt_user_octets_from_client{user="hello"} 6605764944 (6.15 GB)
telemt_user_octets_to_client{user="hello"} 158182227332 (147.32 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 104233.5 (28h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 196805
telemt_connections_bad_total 1658
telemt_handshake_timeouts_total 1481
telemt_upstream_connect_attempt_total 58654
telemt_upstream_connect_success_total 57952
telemt_upstream_connect_fail_total 702
telemt_upstream_connect_attempts_per_request{bucket="1"} 58654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20846
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 573
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 702
telemt_me_keepalive_timeout_total 1360
telemt_me_reconnect_attempts_total 96972
telemt_me_reconnect_success_total 25955
telemt_me_reader_eof_total 28934
telemt_me_idle_close_by_peer_total 28934
telemt_me_route_drop_no_conn_total 79166
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159078
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 23
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
telemt_me_writer_removed_unexpected_total 28398
telemt_me_refill_failed_total 2215
telemt_me_writer_restored_same_endpoint_total 25938
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2443
telemt_user_connections_total{user="hello"} 185651
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 1886351521 (1.76 GB)
telemt_user_octets_to_client{user="hello"} 61291323680 (57.08 GB)
telemt_user_msgs_from_client{user="hello"} 397560
telemt_user_msgs_to_client{user="hello"} 2919853
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 104197.6 (28h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 239248
telemt_connections_bad_total 2065
telemt_handshake_timeouts_total 7767
telemt_upstream_connect_attempt_total 28248
telemt_upstream_connect_success_total 28244
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 28248
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15140
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2176
telemt_me_reconnect_attempts_total 24201
telemt_me_reconnect_success_total 22990
telemt_me_reader_eof_total 24627
telemt_me_idle_close_by_peer_total 24627
telemt_me_route_drop_no_conn_total 88736
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 220746
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 92
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 23243
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 22970
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 253
telemt_user_connections_total{user="hello"} 220660
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 9356826760 (8.71 GB)
telemt_user_octets_to_client{user="hello"} 98052972680 (91.32 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 104172.7 (28h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 334192
telemt_connections_bad_total 14834
telemt_handshake_timeouts_total 2471
telemt_upstream_connect_attempt_total 40043
telemt_upstream_connect_success_total 29967
telemt_upstream_connect_fail_total 10076
telemt_upstream_connect_attempts_per_request{bucket="1"} 40043
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15142
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14614
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 202
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10076
telemt_me_keepalive_timeout_total 4049
telemt_me_reconnect_attempts_total 93260
telemt_me_reconnect_success_total 21708
telemt_me_reader_eof_total 24596
telemt_me_idle_close_by_peer_total 24589
telemt_me_route_drop_no_conn_total 120424
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 287778
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1014
telemt_desync_full_logged_total 300
telemt_desync_suppressed_total 714
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 375
telemt_desync_frames_bucket_total{bucket="gt_10"} 390
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 24214
telemt_me_refill_failed_total 2231
telemt_me_writer_restored_same_endpoint_total 21698
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2506
telemt_user_connections_total{user="hello"} 290689
telemt_user_connections_current{user="hello"} 245
telemt_user_octets_from_client{user="hello"} 5960721158 (5.55 GB)
telemt_user_octets_to_client{user="hello"} 109650653653 (102.12 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 54344.2 (15h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79349
telemt_connections_bad_total 10733
telemt_handshake_timeouts_total 990
telemt_upstream_connect_attempt_total 23490
telemt_upstream_connect_success_total 23305
telemt_upstream_connect_fail_total 185
telemt_upstream_connect_attempts_per_request{bucket="1"} 23490
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12393
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10849
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 185
telemt_me_keepalive_timeout_total 943
telemt_me_reconnect_attempts_total 25572
telemt_me_reconnect_success_total 15655
telemt_me_reader_eof_total 16809
telemt_me_idle_close_by_peer_total 16809
telemt_me_route_drop_no_conn_total 23414
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60050
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 123
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 16102
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 15637
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 447
telemt_user_connections_total{user="hello"} 64960
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 562842881 (536.77 MB)
telemt_user_octets_to_client{user="hello"} 18166365551 (16.92 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 104129.2 (28h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 595951
telemt_connections_bad_total 17527
telemt_handshake_timeouts_total 14537
telemt_upstream_connect_attempt_total 22088
telemt_upstream_connect_success_total 21973
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 22088
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11640
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 2486
telemt_me_reconnect_attempts_total 21413
telemt_me_reconnect_success_total 16792
telemt_me_reader_eof_total 18021
telemt_me_idle_close_by_peer_total 18018
telemt_me_route_drop_no_conn_total 293133
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 570495
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 471
telemt_desync_full_logged_total 176
telemt_desync_suppressed_total 295
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 184
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 17154
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 16785
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 362
telemt_user_connections_total{user="hello"} 543558
telemt_user_connections_current{user="hello"} 456
telemt_user_octets_from_client{user="hello"} 9623324128 (8.96 GB)
telemt_user_octets_to_client{user="hello"} 289614773036 (269.72 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 69
```