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

# Server Metrics 2026-03-19 06:28:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 31226.3 (8h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 494376
telemt_connections_bad_total 52501
telemt_connections_current 1151
telemt_connections_me_current 1151
telemt_handshake_timeouts_total 22232
telemt_upstream_connect_attempt_total 6030
telemt_upstream_connect_success_total 5926
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 6030
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2896
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3027
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 5512
telemt_me_reconnect_success_total 4369
telemt_me_reader_eof_total 4637
telemt_me_idle_close_by_peer_total 4636
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 132646
telemt_me_route_drop_channel_closed_total 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 368402
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2334
telemt_desync_full_logged_total 675
telemt_desync_suppressed_total 1659
telemt_desync_frames_bucket_total{bucket="1_2"} 794
telemt_desync_frames_bucket_total{bucket="3_10"} 915
telemt_desync_frames_bucket_total{bucket="gt_10"} 625
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 4448
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 4352
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 365648
telemt_user_connections_current{user="hello"} 1151
telemt_user_octets_from_client{user="hello"} 4914100784 (4.58 GB)
telemt_user_octets_to_client{user="hello"} 124408613524 (115.86 GB)
telemt_user_unique_ips_current{user="hello"} 451
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 31230.1 (8h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1044682
telemt_connections_bad_total 60276
telemt_connections_current 3543
telemt_connections_me_current 3543
telemt_handshake_timeouts_total 28637
telemt_upstream_connect_attempt_total 5862
telemt_upstream_connect_success_total 5755
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 5862
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2848
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2893
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_reconnect_attempts_total 5329
telemt_me_reconnect_success_total 4183
telemt_me_reader_eof_total 4442
telemt_me_idle_close_by_peer_total 4442
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 337455
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 863483
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3647
telemt_desync_full_logged_total 1252
telemt_desync_suppressed_total 2395
telemt_desync_frames_bucket_total{bucket="1_2"} 662
telemt_desync_frames_bucket_total{bucket="3_10"} 1372
telemt_desync_frames_bucket_total{bucket="gt_10"} 1613
telemt_pool_swap_total 27
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 4295
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 4163
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 863435
telemt_user_connections_current{user="hello"} 3543
telemt_user_octets_from_client{user="hello"} 18758363440 (17.47 GB)
telemt_user_octets_to_client{user="hello"} 384834943064 (358.41 GB)
telemt_user_unique_ips_current{user="hello"} 1259
telemt_user_unique_ips_recent_window{user="hello"} 463
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 31227.2 (8h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 900517
telemt_connections_bad_total 144287
telemt_connections_current 2890
telemt_connections_me_current 2890
telemt_handshake_timeouts_total 27692
telemt_upstream_connect_attempt_total 5718
telemt_upstream_connect_success_total 5718
telemt_upstream_connect_attempts_per_request{bucket="1"} 5718
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2925
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2786
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 4169
telemt_me_reconnect_success_total 4150
telemt_me_reader_eof_total 4395
telemt_me_idle_close_by_peer_total 4395
telemt_me_route_drop_no_conn_total 282548
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 659849
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3339
telemt_desync_full_logged_total 1060
telemt_desync_suppressed_total 2279
telemt_desync_frames_bucket_total{bucket="1_2"} 613
telemt_desync_frames_bucket_total{bucket="3_10"} 1193
telemt_desync_frames_bucket_total{bucket="gt_10"} 1533
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 4226
telemt_me_writer_restored_same_endpoint_total 4134
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 659592
telemt_user_connections_current{user="hello"} 2890
telemt_user_octets_from_client{user="hello"} 12598212292 (11.73 GB)
telemt_user_octets_to_client{user="hello"} 374552867240 (348.83 GB)
telemt_user_unique_ips_current{user="hello"} 977
telemt_user_unique_ips_recent_window{user="hello"} 374
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 31280.5 (8h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 961891
telemt_connections_bad_total 88327
telemt_connections_current 2752
telemt_connections_me_current 2752
telemt_handshake_timeouts_total 23187
telemt_upstream_connect_attempt_total 5510
telemt_upstream_connect_success_total 5510
telemt_upstream_connect_attempts_per_request{bucket="1"} 5510
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2788
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2707
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 4987
telemt_me_reconnect_success_total 3936
telemt_me_reader_eof_total 4184
telemt_me_idle_close_by_peer_total 4183
telemt_me_route_drop_no_conn_total 303125
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 648823
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2506
telemt_desync_full_logged_total 897
telemt_desync_suppressed_total 1609
telemt_desync_frames_bucket_total{bucket="1_2"} 441
telemt_desync_frames_bucket_total{bucket="3_10"} 993
telemt_desync_frames_bucket_total{bucket="gt_10"} 1072
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 4026
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 3912
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 647722
telemt_user_connections_current{user="hello"} 2752
telemt_user_octets_from_client{user="hello"} 10082281700 (9.39 GB)
telemt_user_octets_to_client{user="hello"} 247180159712 (230.20 GB)
telemt_user_unique_ips_current{user="hello"} 936
telemt_user_unique_ips_recent_window{user="hello"} 370
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 31223.6 (8h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1184441
telemt_connections_bad_total 341040
telemt_connections_current 2979
telemt_connections_me_current 2979
telemt_handshake_timeouts_total 29173
telemt_upstream_connect_attempt_total 5564
telemt_upstream_connect_success_total 5529
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 5564
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2720
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_reconnect_attempts_total 3990
telemt_me_reconnect_success_total 3963
telemt_me_reader_eof_total 4194
telemt_me_idle_close_by_peer_total 4194
telemt_me_route_drop_no_conn_total 287566
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 694986
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3447
telemt_desync_full_logged_total 1119
telemt_desync_suppressed_total 2328
telemt_desync_frames_bucket_total{bucket="1_2"} 786
telemt_desync_frames_bucket_total{bucket="3_10"} 1524
telemt_desync_frames_bucket_total{bucket="gt_10"} 1137
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 4007
telemt_me_writer_restored_same_endpoint_total 3939
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 694809
telemt_user_connections_current{user="hello"} 2979
telemt_user_octets_from_client{user="hello"} 16981851084 (15.82 GB)
telemt_user_octets_to_client{user="hello"} 368839511088 (343.51 GB)
telemt_user_unique_ips_current{user="hello"} 1041
telemt_user_unique_ips_recent_window{user="hello"} 444
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 31235.3 (8h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 196069
telemt_connections_bad_total 12198
telemt_connections_current 691
telemt_connections_me_current 691
telemt_handshake_timeouts_total 1573
telemt_upstream_connect_attempt_total 8381
telemt_upstream_connect_success_total 8170
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 8381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3990
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4180
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_reconnect_attempts_total 11047
telemt_me_reconnect_success_total 6609
telemt_me_reader_eof_total 6999
telemt_me_idle_close_by_peer_total 6999
telemt_me_route_drop_no_conn_total 79225
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 171390
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 254
telemt_desync_full_logged_total 88
telemt_desync_suppressed_total 166
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 6773
telemt_me_refill_failed_total 138
telemt_me_writer_restored_same_endpoint_total 6579
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 164
telemt_user_connections_total{user="hello"} 171382
telemt_user_connections_current{user="hello"} 691
telemt_user_octets_from_client{user="hello"} 2783528040 (2.59 GB)
telemt_user_octets_to_client{user="hello"} 92501486888 (86.15 GB)
telemt_user_unique_ips_current{user="hello"} 281
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 31226.2 (8h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 719268
telemt_connections_bad_total 84939
telemt_connections_current 2755
telemt_connections_me_current 2755
telemt_handshake_timeouts_total 31343
telemt_upstream_connect_attempt_total 6244
telemt_upstream_connect_success_total 6244
telemt_upstream_connect_attempts_per_request{bucket="1"} 6244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2926
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 4701
telemt_me_reconnect_success_total 4687
telemt_me_reader_eof_total 4957
telemt_me_idle_close_by_peer_total 4957
telemt_me_route_drop_no_conn_total 251263
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 577008
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3298
telemt_desync_full_logged_total 1174
telemt_desync_suppressed_total 2124
telemt_desync_frames_bucket_total{bucket="1_2"} 647
telemt_desync_frames_bucket_total{bucket="3_10"} 1266
telemt_desync_frames_bucket_total{bucket="gt_10"} 1385
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 4740
telemt_me_writer_restored_same_endpoint_total 4672
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 576814
telemt_user_connections_current{user="hello"} 2755
telemt_user_octets_from_client{user="hello"} 8412604896 (7.83 GB)
telemt_user_octets_to_client{user="hello"} 325866325512 (303.49 GB)
telemt_user_unique_ips_current{user="hello"} 898
telemt_user_unique_ips_recent_window{user="hello"} 338
```