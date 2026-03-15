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

# Server Metrics 2026-03-15 17:41:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 70037.0 (19h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 326852
telemt_connections_bad_total 3665
telemt_handshake_timeouts_total 9497
telemt_upstream_connect_attempt_total 17049
telemt_upstream_connect_success_total 16962
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 17049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9433
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 16867
telemt_me_reconnect_success_total 13472
telemt_me_reader_eof_total 14342
telemt_me_idle_close_by_peer_total 14342
telemt_me_route_drop_no_conn_total 460407
telemt_me_route_drop_channel_closed_total 76
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 361990
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1850
telemt_desync_full_logged_total 734
telemt_desync_suppressed_total 1116
telemt_desync_frames_bucket_total{bucket="1_2"} 343
telemt_desync_frames_bucket_total{bucket="3_10"} 726
telemt_desync_frames_bucket_total{bucket="gt_10"} 781
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 13721
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 13438
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 249
telemt_user_connections_total{user="hello"} 301090
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 6176542168 (5.75 GB)
telemt_user_octets_to_client{user="hello"} 239253832704 (222.82 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 70044.3 (19h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130744
telemt_connections_bad_total 2831
telemt_handshake_timeouts_total 11891
telemt_upstream_connect_attempt_total 19071
telemt_upstream_connect_success_total 19071
telemt_upstream_connect_attempts_per_request{bucket="1"} 19071
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8164
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10625
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 282
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 17903
telemt_me_reconnect_success_total 15539
telemt_me_reader_eof_total 16611
telemt_me_idle_close_by_peer_total 16610
telemt_me_route_drop_no_conn_total 54277
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 110663
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3
telemt_desync_full_logged_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 15813
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 15523
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 274
telemt_user_connections_total{user="hello"} 110644
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 2095443348 (1.95 GB)
telemt_user_octets_to_client{user="hello"} 54173463588 (50.45 GB)
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 70036.8 (19h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134554
telemt_connections_bad_total 1696
telemt_handshake_timeouts_total 3255
telemt_upstream_connect_attempt_total 20581
telemt_upstream_connect_success_total 20573
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 20581
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8921
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11616
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 24383
telemt_me_reconnect_success_total 17027
telemt_me_reader_eof_total 18273
telemt_me_idle_close_by_peer_total 18273
telemt_me_route_drop_no_conn_total 52667
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 118062
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 59
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 17420
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 17019
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 393
telemt_user_connections_total{user="hello"} 117955
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 10676080420 (9.94 GB)
telemt_user_octets_to_client{user="hello"} 67042621148 (62.44 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 70036.6 (19h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183045
telemt_connections_bad_total 928
telemt_handshake_timeouts_total 1207
telemt_upstream_connect_attempt_total 16649
telemt_upstream_connect_success_total 16637
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 16649
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7977
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8592
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 13229
telemt_me_reconnect_success_total 13147
telemt_me_reader_eof_total 13991
telemt_me_idle_close_by_peer_total 13991
telemt_me_route_drop_no_conn_total 70386
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168921
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 584
telemt_desync_full_logged_total 212
telemt_desync_suppressed_total 372
telemt_desync_frames_bucket_total{bucket="1_2"} 121
telemt_desync_frames_bucket_total{bucket="3_10"} 269
telemt_desync_frames_bucket_total{bucket="gt_10"} 194
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 13309
telemt_me_writer_restored_same_endpoint_total 13136
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 168833
telemt_user_connections_current{user="hello"} 247
telemt_user_octets_from_client{user="hello"} 3162271268 (2.95 GB)
telemt_user_octets_to_client{user="hello"} 75171624396 (70.01 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 45108.0 (12h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 111413
telemt_connections_bad_total 23591
telemt_handshake_timeouts_total 2444
telemt_upstream_connect_attempt_total 13610
telemt_upstream_connect_success_total 13532
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 13610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7255
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 105513
telemt_me_reconnect_success_total 11071
telemt_me_reader_eof_total 11618
telemt_me_idle_close_by_peer_total 11618
telemt_me_route_drop_no_conn_total 38228
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 82380
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 219
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 170
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 81
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 11132
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 10967
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 82513
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 1384694997 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 32254980831 (30.04 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 70037.0 (19h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 466590
telemt_connections_bad_total 57621
telemt_handshake_timeouts_total 3821
telemt_upstream_connect_attempt_total 15152
telemt_upstream_connect_success_total 15061
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 15152
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7321
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7712
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 12846
telemt_me_reconnect_success_total 11542
telemt_me_reader_eof_total 12255
telemt_me_idle_close_by_peer_total 12255
telemt_me_route_drop_no_conn_total 286910
telemt_me_route_drop_channel_closed_total 73
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 422214
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 317
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 231
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 11705
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 11515
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 388021
telemt_user_connections_current{user="hello"} 565
telemt_user_octets_from_client{user="hello"} 10246338292 (9.54 GB)
telemt_user_octets_to_client{user="hello"} 206489156064 (192.31 GB)
telemt_user_unique_ips_current{user="hello"} 218
telemt_user_unique_ips_recent_window{user="hello"} 86
```