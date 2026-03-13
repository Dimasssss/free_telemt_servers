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

# Server Metrics 2026-03-13 09:56:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 95010.0 (26h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 374628
telemt_connections_bad_total 3190
telemt_handshake_timeouts_total 7927
telemt_upstream_connect_attempt_total 23999
telemt_upstream_connect_success_total 23887
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 23999
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13077
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1743
telemt_me_reconnect_attempts_total 22631
telemt_me_reconnect_success_total 19113
telemt_me_reader_eof_total 20413
telemt_me_idle_close_by_peer_total 20412
telemt_me_route_drop_no_conn_total 117204
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 321771
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1034
telemt_desync_full_logged_total 384
telemt_desync_suppressed_total 650
telemt_desync_frames_bucket_total{bucket="1_2"} 213
telemt_desync_frames_bucket_total{bucket="3_10"} 375
telemt_desync_frames_bucket_total{bucket="gt_10"} 446
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 19423
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 19097
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 310
telemt_user_connections_total{user="hello"} 321467
telemt_user_connections_current{user="hello"} 382
telemt_user_octets_from_client{user="hello"} 5654021636 (5.27 GB)
telemt_user_octets_to_client{user="hello"} 141248540384 (131.55 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 94902.8 (26h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 171792
telemt_connections_bad_total 1560
telemt_handshake_timeouts_total 1309
telemt_upstream_connect_attempt_total 47038
telemt_upstream_connect_success_total 46397
telemt_upstream_connect_fail_total 641
telemt_upstream_connect_attempts_per_request{bucket="1"} 47038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26735
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19145
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 517
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 641
telemt_me_keepalive_timeout_total 733
telemt_me_reconnect_attempts_total 82803
telemt_me_reconnect_success_total 25154
telemt_me_reader_eof_total 27701
telemt_me_idle_close_by_peer_total 27701
telemt_me_route_drop_no_conn_total 72762
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 145412
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 20
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
telemt_me_writer_removed_unexpected_total 27167
telemt_me_refill_failed_total 1799
telemt_me_writer_restored_same_endpoint_total 25139
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2013
telemt_user_connections_total{user="hello"} 161694
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 1693689700 (1.58 GB)
telemt_user_octets_to_client{user="hello"} 53059279127 (49.42 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 94866.5 (26h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 209108
telemt_connections_bad_total 2025
telemt_handshake_timeouts_total 4211
telemt_upstream_connect_attempt_total 25658
telemt_upstream_connect_success_total 25655
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 25658
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11814
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13816
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 693
telemt_me_reconnect_attempts_total 22054
telemt_me_reconnect_success_total 20863
telemt_me_reader_eof_total 22374
telemt_me_idle_close_by_peer_total 22374
telemt_me_route_drop_no_conn_total 78834
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 195185
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 63
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 21
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 21093
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 20843
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 230
telemt_user_connections_total{user="hello"} 195107
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 9153922220 (8.53 GB)
telemt_user_octets_to_client{user="hello"} 81171355272 (75.60 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 94842.2 (26h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 296317
telemt_connections_bad_total 13666
telemt_handshake_timeouts_total 2155
telemt_upstream_connect_attempt_total 38623
telemt_upstream_connect_success_total 28606
telemt_upstream_connect_fail_total 10017
telemt_upstream_connect_attempts_per_request{bucket="1"} 38623
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14329
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14079
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10017
telemt_me_keepalive_timeout_total 3426
telemt_me_reconnect_attempts_total 80290
telemt_me_reconnect_success_total 20998
telemt_me_reader_eof_total 23494
telemt_me_idle_close_by_peer_total 23487
telemt_me_route_drop_no_conn_total 107283
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 253833
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 941
telemt_desync_full_logged_total 277
telemt_desync_suppressed_total 664
telemt_desync_frames_bucket_total{bucket="1_2"} 239
telemt_desync_frames_bucket_total{bucket="3_10"} 347
telemt_desync_frames_bucket_total{bucket="gt_10"} 355
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 23116
telemt_me_refill_failed_total 1848
telemt_me_writer_restored_same_endpoint_total 20988
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2118
telemt_user_connections_total{user="hello"} 256557
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 5603575242 (5.22 GB)
telemt_user_octets_to_client{user="hello"} 96091018537 (89.49 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 45013.7 (12h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59730
telemt_connections_bad_total 9032
telemt_handshake_timeouts_total 490
telemt_upstream_connect_attempt_total 15437
telemt_upstream_connect_success_total 15289
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 15437
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8545
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_keepalive_timeout_total 378
telemt_me_reconnect_attempts_total 15278
telemt_me_reconnect_success_total 13050
telemt_me_reader_eof_total 13909
telemt_me_idle_close_by_peer_total 13909
telemt_me_route_drop_no_conn_total 18396
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48417
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 76
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 63
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 13236
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 13032
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 48412
telemt_user_connections_current{user="hello"} 68
telemt_user_octets_from_client{user="hello"} 372586128 (355.33 MB)
telemt_user_octets_to_client{user="hello"} 13187164420 (12.28 GB)
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 94798.6 (26h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 516374
telemt_connections_bad_total 14497
telemt_handshake_timeouts_total 6469
telemt_upstream_connect_attempt_total 20204
telemt_upstream_connect_success_total 20098
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 20204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10640
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 1551
telemt_me_reconnect_attempts_total 19023
telemt_me_reconnect_success_total 15370
telemt_me_reader_eof_total 16490
telemt_me_idle_close_by_peer_total 16487
telemt_me_route_drop_no_conn_total 267011
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 504110
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 408
telemt_desync_full_logged_total 158
telemt_desync_suppressed_total 250
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 148
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 15683
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 15363
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 313
telemt_user_connections_total{user="hello"} 477193
telemt_user_connections_current{user="hello"} 492
telemt_user_octets_from_client{user="hello"} 8587290488 (8.00 GB)
telemt_user_octets_to_client{user="hello"} 269060811212 (250.58 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 77
```