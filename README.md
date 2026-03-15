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

# Server Metrics 2026-03-15 17:31:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 69425.8 (19h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 323313
telemt_connections_bad_total 3483
telemt_handshake_timeouts_total 9289
telemt_upstream_connect_attempt_total 16923
telemt_upstream_connect_success_total 16836
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 16923
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7454
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9349
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 16741
telemt_me_reconnect_success_total 13345
telemt_me_reader_eof_total 14209
telemt_me_idle_close_by_peer_total 14209
telemt_me_route_drop_no_conn_total 459536
telemt_me_route_drop_channel_closed_total 76
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 358932
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1846
telemt_desync_full_logged_total 732
telemt_desync_suppressed_total 1114
telemt_desync_frames_bucket_total{bucket="1_2"} 340
telemt_desync_frames_bucket_total{bucket="3_10"} 726
telemt_desync_frames_bucket_total{bucket="gt_10"} 780
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 13595
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 13311
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 250
telemt_user_connections_total{user="hello"} 298032
telemt_user_connections_current{user="hello"} 375
telemt_user_octets_from_client{user="hello"} 6124707160 (5.70 GB)
telemt_user_octets_to_client{user="hello"} 237392470480 (221.09 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 69432.6 (19h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127932
telemt_connections_bad_total 2828
telemt_handshake_timeouts_total 11778
telemt_upstream_connect_attempt_total 18958
telemt_upstream_connect_success_total 18958
telemt_upstream_connect_attempts_per_request{bucket="1"} 18958
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8125
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10560
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 273
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 17790
telemt_me_reconnect_success_total 15427
telemt_me_reader_eof_total 16492
telemt_me_idle_close_by_peer_total 16491
telemt_me_route_drop_no_conn_total 53655
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109067
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
telemt_me_writer_removed_unexpected_total 15698
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 15411
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 271
telemt_user_connections_total{user="hello"} 109050
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 2080206628 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 53904492900 (50.20 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 69425.2 (19h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133014
telemt_connections_bad_total 1695
telemt_handshake_timeouts_total 3219
telemt_upstream_connect_attempt_total 20469
telemt_upstream_connect_success_total 20461
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 20469
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8870
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11555
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 24271
telemt_me_reconnect_success_total 16915
telemt_me_reader_eof_total 18156
telemt_me_idle_close_by_peer_total 18156
telemt_me_route_drop_no_conn_total 52042
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 116612
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
telemt_me_writer_removed_unexpected_total 17306
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 16907
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 391
telemt_user_connections_total{user="hello"} 116505
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 10657445660 (9.93 GB)
telemt_user_octets_to_client{user="hello"} 66503397804 (61.94 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 69424.5 (19h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 180317
telemt_connections_bad_total 927
telemt_handshake_timeouts_total 1172
telemt_upstream_connect_attempt_total 16561
telemt_upstream_connect_success_total 16549
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 16561
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7947
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8535
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 13141
telemt_me_reconnect_success_total 13060
telemt_me_reader_eof_total 13896
telemt_me_idle_close_by_peer_total 13896
telemt_me_route_drop_no_conn_total 69608
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 166321
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 578
telemt_desync_full_logged_total 209
telemt_desync_suppressed_total 369
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 266
telemt_desync_frames_bucket_total{bucket="gt_10"} 192
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 13220
telemt_me_writer_restored_same_endpoint_total 13049
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 166233
telemt_user_connections_current{user="hello"} 273
telemt_user_octets_from_client{user="hello"} 3097348952 (2.88 GB)
telemt_user_octets_to_client{user="hello"} 74390941736 (69.28 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 44496.0 (12h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110056
telemt_connections_bad_total 23481
telemt_handshake_timeouts_total 2432
telemt_upstream_connect_attempt_total 13488
telemt_upstream_connect_success_total 13411
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 13488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7194
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 105437
telemt_me_reconnect_success_total 10996
telemt_me_reader_eof_total 11540
telemt_me_idle_close_by_peer_total 11540
telemt_me_route_drop_no_conn_total 37605
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81227
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 194
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 147
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 76
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 11055
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 10892
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 81360
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 1378353385 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 31833628719 (29.65 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 69424.7 (19h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 461200
telemt_connections_bad_total 57577
telemt_handshake_timeouts_total 3782
telemt_upstream_connect_attempt_total 15027
telemt_upstream_connect_success_total 14936
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 15027
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7651
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 12721
telemt_me_reconnect_success_total 11417
telemt_me_reader_eof_total 12129
telemt_me_idle_close_by_peer_total 12129
telemt_me_route_drop_no_conn_total 282175
telemt_me_route_drop_channel_closed_total 73
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 415763
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
telemt_me_writer_removed_unexpected_total 11579
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 11390
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 382863
telemt_user_connections_current{user="hello"} 580
telemt_user_octets_from_client{user="hello"} 10190425312 (9.49 GB)
telemt_user_octets_to_client{user="hello"} 203900117584 (189.90 GB)
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 73
```