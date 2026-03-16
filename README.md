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

# Server Metrics 2026-03-16 18:07:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 16164.6 (4h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 162052
telemt_connections_bad_total 716
telemt_handshake_timeouts_total 4115
telemt_upstream_connect_attempt_total 3417
telemt_upstream_connect_success_total 3404
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 3417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1616
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1783
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3730
telemt_me_reconnect_success_total 2560
telemt_me_reader_eof_total 2659
telemt_me_idle_close_by_peer_total 2658
telemt_me_route_drop_no_conn_total 49739
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 151883
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 763
telemt_desync_full_logged_total 178
telemt_desync_suppressed_total 585
telemt_desync_frames_bucket_total{bucket="1_2"} 287
telemt_desync_frames_bucket_total{bucket="3_10"} 270
telemt_desync_frames_bucket_total{bucket="gt_10"} 206
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2614
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2558
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 151798
telemt_user_connections_current{user="hello"} 617
telemt_user_octets_from_client{user="hello"} 2849987500 (2.65 GB)
telemt_user_octets_to_client{user="hello"} 87097114204 (81.12 GB)
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 10943.1 (3h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76804
telemt_connections_bad_total 637
telemt_handshake_timeouts_total 3206
telemt_upstream_connect_attempt_total 2321
telemt_upstream_connect_success_total 2308
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2321
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 826
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1278
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 204
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 5202
telemt_me_reconnect_success_total 1692
telemt_me_reader_eof_total 1838
telemt_me_idle_close_by_peer_total 1838
telemt_me_route_drop_no_conn_total 44165
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 70212
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 114
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 86
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1834
telemt_me_refill_failed_total 109
telemt_me_writer_restored_same_endpoint_total 1687
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 343
telemt_me_writer_removed_unexpected_minus_restored_total 142
telemt_user_connections_total{user="hello"} 70153
telemt_user_connections_current{user="hello"} 382
telemt_user_octets_from_client{user="hello"} 819386524 (781.43 MB)
telemt_user_octets_to_client{user="hello"} 20541133108 (19.13 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 16277.5 (4h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65885
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 884
telemt_upstream_connect_attempt_total 4797
telemt_upstream_connect_success_total 4749
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 4796
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2230
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 41787
telemt_me_reconnect_success_total 2901
telemt_me_reader_eof_total 3252
telemt_me_idle_close_by_peer_total 3252
telemt_me_route_drop_no_conn_total 23308
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60855
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 163
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 72
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 3236
telemt_me_refill_failed_total 1214
telemt_me_writer_restored_same_endpoint_total 2857
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 335
telemt_user_connections_total{user="hello"} 61789
telemt_user_connections_current{user="hello"} 258
telemt_user_octets_from_client{user="hello"} 826984934 (788.67 MB)
telemt_user_octets_to_client{user="hello"} 17142493018 (15.97 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 16413.8 (4h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127899
telemt_connections_bad_total 231
telemt_handshake_timeouts_total 1768
telemt_upstream_connect_attempt_total 3542
telemt_upstream_connect_success_total 3516
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 3542
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1799
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 8952
telemt_me_reconnect_success_total 2595
telemt_me_reader_eof_total 2855
telemt_me_idle_close_by_peer_total 2854
telemt_me_route_drop_no_conn_total 46732
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 121422
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 665
telemt_desync_full_logged_total 188
telemt_desync_suppressed_total 477
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 277
telemt_desync_frames_bucket_total{bucket="gt_10"} 274
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2827
telemt_me_refill_failed_total 197
telemt_me_writer_restored_same_endpoint_total 2591
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 232
telemt_user_connections_total{user="hello"} 121391
telemt_user_connections_current{user="hello"} 443
telemt_user_octets_from_client{user="hello"} 1690089836 (1.57 GB)
telemt_user_octets_to_client{user="hello"} 30293496272 (28.21 GB)
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 13874.2 (3h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72732
telemt_connections_bad_total 20472
telemt_handshake_timeouts_total 575
telemt_upstream_connect_attempt_total 3660
telemt_upstream_connect_success_total 3604
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 3660
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1461
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2058
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_reconnect_attempts_total 4523
telemt_me_reconnect_success_total 2860
telemt_me_reader_eof_total 2964
telemt_me_idle_close_by_peer_total 2964
telemt_me_route_drop_no_conn_total 51508
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68032
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 65
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 41
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3013
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 2860
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 153
telemt_user_connections_total{user="hello"} 49075
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 2079257232 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 33328152204 (31.04 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 15989.5 (4h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184748
telemt_connections_bad_total 2195
telemt_handshake_timeouts_total 3405
telemt_upstream_connect_attempt_total 3298
telemt_upstream_connect_success_total 3297
telemt_upstream_connect_attempts_per_request{bucket="1"} 3297
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1561
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1726
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7481
telemt_me_reconnect_success_total 2452
telemt_me_reader_eof_total 2668
telemt_me_idle_close_by_peer_total 2667
telemt_me_route_drop_no_conn_total 84139
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 171640
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 106
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 67
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2631
telemt_me_refill_failed_total 156
telemt_me_writer_restored_same_endpoint_total 2446
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 171304
telemt_user_connections_current{user="hello"} 770
telemt_user_octets_from_client{user="hello"} 3267846104 (3.04 GB)
telemt_user_octets_to_client{user="hello"} 64759207312 (60.31 GB)
telemt_user_unique_ips_current{user="hello"} 262
telemt_user_unique_ips_recent_window{user="hello"} 81
```