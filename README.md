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

# Server Metrics 2026-03-19 12:01:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 51180.2 (14h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1254048
telemt_connections_bad_total 103617
telemt_connections_current 1770
telemt_connections_me_current 1770
telemt_handshake_timeouts_total 44415
telemt_upstream_connect_attempt_total 9781
telemt_upstream_connect_success_total 9614
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 9781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4905
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 8940
telemt_me_reconnect_success_total 7052
telemt_me_reader_eof_total 7462
telemt_me_idle_close_by_peer_total 7459
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 518315
telemt_me_route_drop_channel_closed_total 203
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 983604
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 35
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5477
telemt_desync_full_logged_total 1670
telemt_desync_suppressed_total 3807
telemt_desync_frames_bucket_total{bucket="1_2"} 1756
telemt_desync_frames_bucket_total{bucket="3_10"} 1987
telemt_desync_frames_bucket_total{bucket="gt_10"} 1734
telemt_pool_swap_total 40
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 7212
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 7031
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 977511
telemt_user_connections_current{user="hello"} 1770
telemt_user_octets_from_client{user="hello"} 15121212304 (14.08 GB)
telemt_user_octets_to_client{user="hello"} 295744070272 (275.43 GB)
telemt_user_unique_ips_current{user="hello"} 591
telemt_user_unique_ips_recent_window{user="hello"} 294
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 51184.0 (14h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3557504
telemt_connections_bad_total 230081
telemt_connections_current 4191
telemt_connections_me_current 4191
telemt_handshake_timeouts_total 62993
telemt_upstream_connect_attempt_total 9586
telemt_upstream_connect_success_total 9409
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 9586
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4764
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4614
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 16924
telemt_me_reconnect_success_total 6818
telemt_me_reader_eof_total 7451
telemt_me_idle_close_by_peer_total 7450
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 3048804
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2998321
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11467
telemt_desync_full_logged_total 3853
telemt_desync_suppressed_total 7614
telemt_desync_frames_bucket_total{bucket="1_2"} 2232
telemt_desync_frames_bucket_total{bucket="3_10"} 4517
telemt_desync_frames_bucket_total{bucket="gt_10"} 4718
telemt_pool_swap_total 33
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 7254
telemt_me_refill_failed_total 315
telemt_me_writer_restored_same_endpoint_total 6795
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 436
telemt_user_connections_total{user="hello"} 2997935
telemt_user_connections_current{user="hello"} 4191
telemt_user_octets_from_client{user="hello"} 37634344200 (35.05 GB)
telemt_user_octets_to_client{user="hello"} 849711162028 (791.36 GB)
telemt_user_unique_ips_current{user="hello"} 1368
telemt_user_unique_ips_recent_window{user="hello"} 1081
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 51181.5 (14h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2655726
telemt_connections_bad_total 311695
telemt_connections_current 3381
telemt_connections_me_current 3381
telemt_handshake_timeouts_total 52777
telemt_upstream_connect_attempt_total 9270
telemt_upstream_connect_success_total 9269
telemt_upstream_connect_attempts_per_request{bucket="1"} 9269
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4445
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 7870
telemt_me_reconnect_success_total 6674
telemt_me_reader_eof_total 7073
telemt_me_idle_close_by_peer_total 7072
telemt_me_route_drop_no_conn_total 1640857
telemt_me_route_drop_channel_closed_total 87
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2091415
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8596
telemt_desync_full_logged_total 2728
telemt_desync_suppressed_total 5868
telemt_desync_frames_bucket_total{bucket="1_2"} 1945
telemt_desync_frames_bucket_total{bucket="3_10"} 3156
telemt_desync_frames_bucket_total{bucket="gt_10"} 3495
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 6826
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 6658
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 152
telemt_user_connections_total{user="hello"} 2089170
telemt_user_connections_current{user="hello"} 3381
telemt_user_octets_from_client{user="hello"} 28917178464 (26.93 GB)
telemt_user_octets_to_client{user="hello"} 884894071072 (824.12 GB)
telemt_user_unique_ips_current{user="hello"} 1205
telemt_user_unique_ips_recent_window{user="hello"} 706
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 51234.7 (14h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2703581
telemt_connections_bad_total 141329
telemt_connections_current 3237
telemt_connections_me_current 3237
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 66187
telemt_upstream_connect_attempt_total 17578
telemt_upstream_connect_success_total 17397
telemt_upstream_connect_fail_total 181
telemt_upstream_connect_attempts_per_request{bucket="1"} 17578
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12070
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5158
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 167
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 181
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 10996
telemt_me_reconnect_success_total 6643
telemt_me_reader_eof_total 7068
telemt_me_idle_close_by_peer_total 7067
telemt_me_route_drop_no_conn_total 1759509
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2100014
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7480
telemt_desync_full_logged_total 2490
telemt_desync_suppressed_total 4990
telemt_desync_frames_bucket_total{bucket="1_2"} 1579
telemt_desync_frames_bucket_total{bucket="3_10"} 2938
telemt_desync_frames_bucket_total{bucket="gt_10"} 2963
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7117
telemt_me_refill_failed_total 128
telemt_me_writer_restored_same_endpoint_total 6619
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 295
telemt_me_writer_removed_unexpected_minus_restored_total 474
telemt_user_connections_total{user="hello"} 2106100
telemt_user_connections_current{user="hello"} 3237
telemt_user_octets_from_client{user="hello"} 23627714652 (22.01 GB)
telemt_user_octets_to_client{user="hello"} 565815592258 (526.96 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 1049
telemt_user_unique_ips_recent_window{user="hello"} 530
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 51178.6 (14h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3236409
telemt_connections_bad_total 684215
telemt_connections_current 2741
telemt_connections_direct_current 2737
telemt_connections_me_current 4
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 63808
telemt_upstream_connect_attempt_total 26948
telemt_upstream_connect_success_total 24475
telemt_upstream_connect_fail_total 2464
telemt_upstream_connect_attempts_per_request{bucket="1"} 26939
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5463
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 782
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2464
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 69423
telemt_me_reconnect_success_total 6599
telemt_me_reader_eof_total 6882
telemt_me_idle_close_by_peer_total 6879
telemt_me_route_drop_no_conn_total 1405159
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2154846
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9167
telemt_desync_full_logged_total 2850
telemt_desync_suppressed_total 6317
telemt_desync_frames_bucket_total{bucket="1_2"} 1736
telemt_desync_frames_bucket_total{bucket="3_10"} 3954
telemt_desync_frames_bucket_total{bucket="gt_10"} 3477
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 6642
telemt_me_refill_failed_total 1960
telemt_me_writer_restored_same_endpoint_total 6575
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 2170067
telemt_user_connections_current{user="hello"} 2741
telemt_user_octets_from_client{user="hello"} 35760832301 (33.30 GB)
telemt_user_octets_to_client{user="hello"} 828555792810 (771.65 GB)
telemt_user_msgs_from_client{user="hello"} 83820
telemt_user_msgs_to_client{user="hello"} 304204
telemt_user_unique_ips_current{user="hello"} 821
telemt_user_unique_ips_recent_window{user="hello"} 1195
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 51190.4 (14h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 547790
telemt_connections_bad_total 18972
telemt_connections_current 1140
telemt_connections_me_current 1140
telemt_handshake_timeouts_total 4283
telemt_upstream_connect_attempt_total 12601
telemt_upstream_connect_success_total 12277
telemt_upstream_connect_fail_total 324
telemt_upstream_connect_attempts_per_request{bucket="1"} 12601
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6244
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 324
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 17294
telemt_me_reconnect_success_total 9702
telemt_me_reader_eof_total 10340
telemt_me_idle_close_by_peer_total 10340
telemt_me_route_drop_no_conn_total 283664
telemt_me_route_drop_channel_closed_total 38
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 497924
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1123
telemt_desync_full_logged_total 393
telemt_desync_suppressed_total 730
telemt_desync_frames_bucket_total{bucket="1_2"} 225
telemt_desync_frames_bucket_total{bucket="3_10"} 457
telemt_desync_frames_bucket_total{bucket="gt_10"} 441
telemt_pool_swap_total 24
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 10031
telemt_me_refill_failed_total 235
telemt_me_writer_restored_same_endpoint_total 9671
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 329
telemt_user_connections_total{user="hello"} 497855
telemt_user_connections_current{user="hello"} 1140
telemt_user_octets_from_client{user="hello"} 8008909752 (7.46 GB)
telemt_user_octets_to_client{user="hello"} 180828442924 (168.41 GB)
telemt_user_unique_ips_current{user="hello"} 372
telemt_user_unique_ips_recent_window{user="hello"} 228
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 51180.5 (14h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2206151
telemt_connections_bad_total 178926
telemt_connections_current 3475
telemt_connections_me_current 3475
telemt_handshake_timeouts_total 73536
telemt_upstream_connect_attempt_total 10319
telemt_upstream_connect_success_total 10318
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4718
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 9093
telemt_me_reconnect_success_total 7721
telemt_me_reader_eof_total 8159
telemt_me_idle_close_by_peer_total 8158
telemt_me_route_drop_no_conn_total 1104429
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1849590
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10119
telemt_desync_full_logged_total 3243
telemt_desync_suppressed_total 6876
telemt_desync_frames_bucket_total{bucket="1_2"} 1930
telemt_desync_frames_bucket_total{bucket="3_10"} 3847
telemt_desync_frames_bucket_total{bucket="gt_10"} 4342
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 7863
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 7706
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 142
telemt_user_connections_total{user="hello"} 1848382
telemt_user_connections_current{user="hello"} 3475
telemt_user_octets_from_client{user="hello"} 24349250896 (22.68 GB)
telemt_user_octets_to_client{user="hello"} 823169240584 (766.64 GB)
telemt_user_unique_ips_current{user="hello"} 1083
telemt_user_unique_ips_recent_window{user="hello"} 659
```