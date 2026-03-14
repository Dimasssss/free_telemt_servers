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

# Server Metrics 2026-03-14 08:19:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 175546.3 (48h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 675068
telemt_connections_bad_total 32479
telemt_handshake_timeouts_total 13243
telemt_upstream_connect_attempt_total 44617
telemt_upstream_connect_success_total 44389
telemt_upstream_connect_fail_total 228
telemt_upstream_connect_attempts_per_request{bucket="1"} 44617
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20322
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23915
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 228
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5746
telemt_me_reconnect_attempts_total 39968
telemt_me_reconnect_success_total 35273
telemt_me_reader_eof_total 37708
telemt_me_idle_close_by_peer_total 37707
telemt_me_route_drop_no_conn_total 223333
telemt_me_route_drop_channel_closed_total 31
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 575801
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2235
telemt_desync_full_logged_total 758
telemt_desync_suppressed_total 1477
telemt_desync_frames_bucket_total{bucket="1_2"} 483
telemt_desync_frames_bucket_total{bucket="3_10"} 819
telemt_desync_frames_bucket_total{bucket="gt_10"} 933
telemt_pool_swap_total 161
telemt_me_writer_removed_unexpected_total 35798
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 35253
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 525
telemt_user_connections_total{user="hello"} 575688
telemt_user_connections_current{user="hello"} 382
telemt_user_octets_from_client{user="hello"} 16753238102 (15.60 GB)
telemt_user_octets_to_client{user="hello"} 275931684960 (256.98 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 175438.8 (48h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 339889
telemt_connections_bad_total 2329
telemt_handshake_timeouts_total 2996
telemt_upstream_connect_attempt_total 151814
telemt_upstream_connect_success_total 150515
telemt_upstream_connect_fail_total 1299
telemt_upstream_connect_attempts_per_request{bucket="1"} 151814
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 110485
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37592
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1299
telemt_me_keepalive_timeout_total 5309
telemt_me_reconnect_attempts_total 179086
telemt_me_reconnect_success_total 38482
telemt_me_reader_eof_total 43924
telemt_me_idle_close_by_peer_total 43924
telemt_me_route_drop_no_conn_total 114130
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 218064
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 43
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
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 43249
telemt_me_refill_failed_total 4387
telemt_me_writer_restored_same_endpoint_total 38465
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4767
telemt_user_connections_total{user="hello"} 321170
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 3312833271 (3.09 GB)
telemt_user_octets_to_client{user="hello"} 104334464143 (97.17 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 175402.3 (48h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 397182
telemt_connections_bad_total 3193
telemt_handshake_timeouts_total 35330
telemt_upstream_connect_attempt_total 46235
telemt_upstream_connect_success_total 46226
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 46235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25017
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3507
telemt_me_reconnect_attempts_total 38754
telemt_me_reconnect_success_total 37464
telemt_me_reader_eof_total 40286
telemt_me_idle_close_by_peer_total 40286
telemt_me_route_drop_no_conn_total 143618
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 344730
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 113
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 63
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 37919
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 37443
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 455
telemt_user_connections_total{user="hello"} 344491
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 13644500068 (12.71 GB)
telemt_user_octets_to_client{user="hello"} 142937424348 (133.12 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 175377.8 (48h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 499475
telemt_connections_bad_total 16275
telemt_handshake_timeouts_total 4571
telemt_upstream_connect_attempt_total 76781
telemt_upstream_connect_success_total 66162
telemt_upstream_connect_fail_total 10619
telemt_upstream_connect_attempts_per_request{bucket="1"} 76781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38866
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26944
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 343
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10619
telemt_me_keepalive_timeout_total 5472
telemt_me_reconnect_attempts_total 146873
telemt_me_reconnect_success_total 38410
telemt_me_reader_eof_total 43028
telemt_me_idle_close_by_peer_total 43020
telemt_me_route_drop_no_conn_total 180879
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 426239
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1851
telemt_desync_full_logged_total 551
telemt_desync_suppressed_total 1300
telemt_desync_frames_bucket_total{bucket="1_2"} 437
telemt_desync_frames_bucket_total{bucket="3_10"} 708
telemt_desync_frames_bucket_total{bucket="gt_10"} 706
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 42237
telemt_me_refill_failed_total 3382
telemt_me_writer_restored_same_endpoint_total 38400
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3827
telemt_user_connections_total{user="hello"} 445119
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 9551609423 (8.90 GB)
telemt_user_octets_to_client{user="hello"} 183099956548 (170.53 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 125549.4 (34h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 205795
telemt_connections_bad_total 31179
telemt_handshake_timeouts_total 1765
telemt_upstream_connect_attempt_total 44133
telemt_upstream_connect_success_total 43708
telemt_upstream_connect_fail_total 425
telemt_upstream_connect_attempts_per_request{bucket="1"} 44133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21869
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21695
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 425
telemt_me_keepalive_timeout_total 2559
telemt_me_reconnect_attempts_total 46008
telemt_me_reconnect_success_total 32571
telemt_me_reader_eof_total 34837
telemt_me_idle_close_by_peer_total 34837
telemt_me_route_drop_no_conn_total 61549
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162325
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 701
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 530
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 335
telemt_desync_frames_bucket_total{bucket="gt_10"} 252
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 33290
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 32553
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 719
telemt_user_connections_total{user="hello"} 167085
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 2462617177 (2.29 GB)
telemt_user_octets_to_client{user="hello"} 79603281763 (74.14 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 175334.1 (48h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1007493
telemt_connections_bad_total 36304
telemt_handshake_timeouts_total 26247
telemt_upstream_connect_attempt_total 36385
telemt_upstream_connect_success_total 36191
telemt_upstream_connect_fail_total 194
telemt_upstream_connect_attempts_per_request{bucket="1"} 36385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17018
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19132
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 194
telemt_me_keepalive_timeout_total 4752
telemt_me_reconnect_attempts_total 32214
telemt_me_reconnect_success_total 27532
telemt_me_reader_eof_total 29541
telemt_me_idle_close_by_peer_total 29538
telemt_me_route_drop_no_conn_total 473452
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 933782
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 770
telemt_desync_full_logged_total 254
telemt_desync_suppressed_total 516
telemt_desync_frames_bucket_total{bucket="1_2"} 257
telemt_desync_frames_bucket_total{bucket="3_10"} 253
telemt_desync_frames_bucket_total{bucket="gt_10"} 260
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 28027
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 27525
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 495
telemt_user_connections_total{user="hello"} 906415
telemt_user_connections_current{user="hello"} 435
telemt_user_octets_from_client{user="hello"} 15399878360 (14.34 GB)
telemt_user_octets_to_client{user="hello"} 451345057700 (420.35 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 59
```