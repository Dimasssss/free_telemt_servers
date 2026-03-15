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

# Server Metrics 2026-03-15 17:57:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 70956.4 (19h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 332045
telemt_connections_bad_total 4184
telemt_handshake_timeouts_total 10255
telemt_upstream_connect_attempt_total 17244
telemt_upstream_connect_success_total 17157
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 17244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7588
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9535
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 17019
telemt_me_reconnect_success_total 13623
telemt_me_reader_eof_total 14505
telemt_me_idle_close_by_peer_total 14505
telemt_me_route_drop_no_conn_total 461816
telemt_me_route_drop_channel_closed_total 76
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 365750
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1855
telemt_desync_full_logged_total 738
telemt_desync_suppressed_total 1117
telemt_desync_frames_bucket_total{bucket="1_2"} 347
telemt_desync_frames_bucket_total{bucket="3_10"} 727
telemt_desync_frames_bucket_total{bucket="gt_10"} 781
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 13873
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 13589
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 250
telemt_user_connections_total{user="hello"} 304850
telemt_user_connections_current{user="hello"} 331
telemt_user_octets_from_client{user="hello"} 6234341912 (5.81 GB)
telemt_user_octets_to_client{user="hello"} 240898229644 (224.35 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 70963.1 (19h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132987
telemt_connections_bad_total 2834
telemt_handshake_timeouts_total 12078
telemt_upstream_connect_attempt_total 19288
telemt_upstream_connect_success_total 19288
telemt_upstream_connect_attempts_per_request{bucket="1"} 19288
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10748
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 296
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 18077
telemt_me_reconnect_success_total 15711
telemt_me_reader_eof_total 16795
telemt_me_idle_close_by_peer_total 16794
telemt_me_route_drop_no_conn_total 55056
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 112599
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
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 15989
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 15695
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 278
telemt_user_connections_total{user="hello"} 112580
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 2122658828 (1.98 GB)
telemt_user_octets_to_client{user="hello"} 55980773404 (52.14 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 70955.6 (19h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137183
telemt_connections_bad_total 1696
telemt_handshake_timeouts_total 3276
telemt_upstream_connect_attempt_total 20791
telemt_upstream_connect_success_total 20783
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 20791
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9014
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11733
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 24550
telemt_me_reconnect_success_total 17193
telemt_me_reader_eof_total 18451
telemt_me_idle_close_by_peer_total 18451
telemt_me_route_drop_no_conn_total 53631
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 120510
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
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 17588
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 17185
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 395
telemt_user_connections_total{user="hello"} 120402
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 10698565528 (9.96 GB)
telemt_user_octets_to_client{user="hello"} 67955040652 (63.29 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 70955.4 (19h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 187157
telemt_connections_bad_total 940
telemt_handshake_timeouts_total 1243
telemt_upstream_connect_attempt_total 16816
telemt_upstream_connect_success_total 16804
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 16816
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8050
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8685
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 13353
telemt_me_reconnect_success_total 13270
telemt_me_reader_eof_total 14121
telemt_me_idle_close_by_peer_total 14121
telemt_me_route_drop_no_conn_total 71270
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 172537
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 606
telemt_desync_full_logged_total 221
telemt_desync_suppressed_total 385
telemt_desync_frames_bucket_total{bucket="1_2"} 128
telemt_desync_frames_bucket_total{bucket="3_10"} 280
telemt_desync_frames_bucket_total{bucket="gt_10"} 198
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 13432
telemt_me_writer_restored_same_endpoint_total 13259
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 172449
telemt_user_connections_current{user="hello"} 272
telemt_user_octets_from_client{user="hello"} 3207253736 (2.99 GB)
telemt_user_octets_to_client{user="hello"} 78020614028 (72.66 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 46026.8 (12h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113619
telemt_connections_bad_total 23759
telemt_handshake_timeouts_total 2458
telemt_upstream_connect_attempt_total 13783
telemt_upstream_connect_success_total 13703
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 13783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7347
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 105641
telemt_me_reconnect_success_total 11197
telemt_me_reader_eof_total 11757
telemt_me_idle_close_by_peer_total 11757
telemt_me_route_drop_no_conn_total 38995
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 84247
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 242
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 190
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 89
telemt_desync_frames_bucket_total{bucket="gt_10"} 110
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 11263
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 11093
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 84380
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 1436244713 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 33115579039 (30.84 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 70956.0 (19h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 474541
telemt_connections_bad_total 57629
telemt_handshake_timeouts_total 3874
telemt_upstream_connect_attempt_total 15332
telemt_upstream_connect_success_total 15241
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 15332
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7389
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7823
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 12983
telemt_me_reconnect_success_total 11678
telemt_me_reader_eof_total 12406
telemt_me_idle_close_by_peer_total 12406
telemt_me_route_drop_no_conn_total 299508
telemt_me_route_drop_channel_closed_total 75
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 433985
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
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 11843
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 11651
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 395632
telemt_user_connections_current{user="hello"} 636
telemt_user_octets_from_client{user="hello"} 10359147272 (9.65 GB)
telemt_user_octets_to_client{user="hello"} 212531057776 (197.93 GB)
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 71
```