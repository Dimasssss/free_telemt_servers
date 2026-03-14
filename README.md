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

# Server Metrics 2026-03-14 17:39:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 15804.1 (4h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90438
telemt_connections_bad_total 13725
telemt_handshake_timeouts_total 483
telemt_upstream_connect_attempt_total 3789
telemt_upstream_connect_success_total 3787
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 3789
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1817
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1897
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 2973
telemt_me_reconnect_success_total 2943
telemt_me_reader_eof_total 3103
telemt_me_idle_close_by_peer_total 3103
telemt_me_route_drop_no_conn_total 32403
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72950
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 305
telemt_desync_full_logged_total 112
telemt_desync_suppressed_total 193
telemt_desync_frames_bucket_total{bucket="1_2"} 71
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 118
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2994
telemt_me_writer_restored_same_endpoint_total 2925
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 72879
telemt_user_connections_current{user="hello"} 364
telemt_user_octets_from_client{user="hello"} 1533736120 (1.43 GB)
telemt_user_octets_to_client{user="hello"} 34210490440 (31.86 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 15802.1 (4h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37025
telemt_connections_bad_total 451
telemt_handshake_timeouts_total 752
telemt_upstream_connect_attempt_total 4398
telemt_upstream_connect_success_total 4364
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 4398
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2519
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 6093
telemt_me_reconnect_success_total 3520
telemt_me_reader_eof_total 3735
telemt_me_idle_close_by_peer_total 3735
telemt_me_route_drop_no_conn_total 19114
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34508
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 3653
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 3515
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 34490
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 444470176 (423.88 MB)
telemt_user_octets_to_client{user="hello"} 13896946692 (12.94 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 15808.3 (4h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38580
telemt_connections_bad_total 352
telemt_handshake_timeouts_total 1696
telemt_upstream_connect_attempt_total 6102
telemt_upstream_connect_success_total 6040
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 6102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3082
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 109
telemt_me_reconnect_attempts_total 102735
telemt_me_reconnect_success_total 4880
telemt_me_reader_eof_total 5197
telemt_me_idle_close_by_peer_total 5197
telemt_me_route_drop_no_conn_total 15164
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34290
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 5137
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 4842
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 257
telemt_user_connections_total{user="hello"} 34414
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 2813925049 (2.62 GB)
telemt_user_octets_to_client{user="hello"} 17424700446 (16.23 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 15810.9 (4h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49497
telemt_connections_bad_total 117
telemt_handshake_timeouts_total 313
telemt_upstream_connect_attempt_total 4100
telemt_upstream_connect_success_total 4077
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 4100
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1850
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2207
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 91
telemt_me_reconnect_attempts_total 3262
telemt_me_reconnect_success_total 3242
telemt_me_reader_eof_total 3378
telemt_me_idle_close_by_peer_total 3378
telemt_me_route_drop_no_conn_total 23039
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46975
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 421
telemt_desync_full_logged_total 108
telemt_desync_suppressed_total 313
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 174
telemt_desync_frames_bucket_total{bucket="gt_10"} 178
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 3275
telemt_me_writer_restored_same_endpoint_total 3240
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 46854
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 573502088 (546.93 MB)
telemt_user_octets_to_client{user="hello"} 15312041340 (14.26 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 15804.1 (4h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35972
telemt_connections_bad_total 3077
telemt_handshake_timeouts_total 1920
telemt_upstream_connect_attempt_total 3657
telemt_upstream_connect_success_total 3615
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 3657
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2016
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 9294
telemt_me_reconnect_success_total 2772
telemt_me_reader_eof_total 3046
telemt_me_idle_close_by_peer_total 3046
telemt_me_route_drop_no_conn_total 12398
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29351
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 125
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 111
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 63
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2995
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 2768
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 223
telemt_user_connections_total{user="hello"} 29345
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 526402452 (502.02 MB)
telemt_user_octets_to_client{user="hello"} 7965892204 (7.42 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 15803.8 (4h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128477
telemt_connections_bad_total 6994
telemt_handshake_timeouts_total 1501
telemt_upstream_connect_attempt_total 3318
telemt_upstream_connect_success_total 3252
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 3318
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1604
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1646
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 82
telemt_me_reconnect_attempts_total 7404
telemt_me_reconnect_success_total 2407
telemt_me_reader_eof_total 2625
telemt_me_idle_close_by_peer_total 2625
telemt_me_route_drop_no_conn_total 65955
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 114286
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2583
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 2403
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 113591
telemt_user_connections_current{user="hello"} 564
telemt_user_octets_from_client{user="hello"} 2651003836 (2.47 GB)
telemt_user_octets_to_client{user="hello"} 57001556968 (53.09 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 72
```