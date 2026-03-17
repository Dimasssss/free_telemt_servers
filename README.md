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

# Server Metrics 2026-03-17 07:20:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 45310.1 (12h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 291493
telemt_connections_bad_total 3509
telemt_handshake_timeouts_total 9407
telemt_upstream_connect_attempt_total 9382
telemt_upstream_connect_success_total 9331
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 9382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4273
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5052
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7095
telemt_me_reconnect_success_total 7068
telemt_me_reader_eof_total 7527
telemt_me_idle_close_by_peer_total 7527
telemt_me_route_drop_no_conn_total 88819
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 261402
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1961
telemt_desync_full_logged_total 581
telemt_desync_suppressed_total 1380
telemt_desync_frames_bucket_total{bucket="1_2"} 422
telemt_desync_frames_bucket_total{bucket="3_10"} 996
telemt_desync_frames_bucket_total{bucket="gt_10"} 543
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 7141
telemt_me_writer_restored_same_endpoint_total 7047
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 261178
telemt_user_connections_current{user="hello"} 777
telemt_user_octets_from_client{user="hello"} 3467447912 (3.23 GB)
telemt_user_octets_to_client{user="hello"} 114906858280 (107.02 GB)
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 45562.2 (12h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 164753
telemt_connections_bad_total 2347
telemt_handshake_timeouts_total 11771
telemt_upstream_connect_attempt_total 12461
telemt_upstream_connect_success_total 12300
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 12461
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7002
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_reconnect_attempts_total 11226
telemt_me_reconnect_success_total 10043
telemt_me_reader_eof_total 10613
telemt_me_idle_close_by_peer_total 10613
telemt_me_route_drop_no_conn_total 59541
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 142158
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 376
telemt_desync_full_logged_total 133
telemt_desync_suppressed_total 243
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 171
telemt_desync_frames_bucket_total{bucket="gt_10"} 103
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 10173
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 10027
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 142208
telemt_user_connections_current{user="hello"} 422
telemt_user_octets_from_client{user="hello"} 1754792828 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 59479724232 (55.39 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 45338.3 (12h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97790
telemt_connections_bad_total 2077
telemt_handshake_timeouts_total 3989
telemt_upstream_connect_attempt_total 11966
telemt_upstream_connect_success_total 11903
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 11966
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5276
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6565
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 9673
telemt_me_reconnect_success_total 9618
telemt_me_reader_eof_total 10300
telemt_me_idle_close_by_peer_total 10300
telemt_me_route_drop_no_conn_total 32073
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 83222
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 99
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 66
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 9737
telemt_me_writer_restored_same_endpoint_total 9607
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 119
telemt_user_connections_total{user="hello"} 83179
telemt_user_connections_current{user="hello"} 244
telemt_user_octets_from_client{user="hello"} 6316588392 (5.88 GB)
telemt_user_octets_to_client{user="hello"} 25997873740 (24.21 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 45397.6 (12h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 189365
telemt_connections_bad_total 5828
telemt_handshake_timeouts_total 9890
telemt_upstream_connect_attempt_total 10373
telemt_upstream_connect_success_total 10286
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 10373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4863
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5356
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 8023
telemt_me_reconnect_success_total 7958
telemt_me_reader_eof_total 8453
telemt_me_idle_close_by_peer_total 8453
telemt_me_route_drop_no_conn_total 57492
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159804
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 300
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 200
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 118
telemt_desync_frames_bucket_total{bucket="gt_10"} 113
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 8073
telemt_me_writer_restored_same_endpoint_total 7950
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 159811
telemt_user_connections_current{user="hello"} 522
telemt_user_octets_from_client{user="hello"} 1707895918 (1.59 GB)
telemt_user_octets_to_client{user="hello"} 73756687393 (68.69 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 45369.5 (12h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128818
telemt_connections_bad_total 38253
telemt_handshake_timeouts_total 2401
telemt_upstream_connect_attempt_total 13833
telemt_upstream_connect_success_total 13654
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 13833
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6132
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7332
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 190
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_reconnect_attempts_total 14530
telemt_me_reconnect_success_total 11268
telemt_me_reader_eof_total 11911
telemt_me_idle_close_by_peer_total 11911
telemt_me_route_drop_no_conn_total 33428
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 84653
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 84
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 54
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 11512
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 11260
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 244
telemt_user_connections_total{user="hello"} 84697
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 848955871 (809.63 MB)
telemt_user_octets_to_client{user="hello"} 39681075722 (36.96 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 45530.9 (12h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 304931
telemt_connections_bad_total 42160
telemt_handshake_timeouts_total 2596
telemt_upstream_connect_attempt_total 9385
telemt_upstream_connect_success_total 9337
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 9385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4833
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 7104
telemt_me_reconnect_success_total 7070
telemt_me_reader_eof_total 7552
telemt_me_idle_close_by_peer_total 7552
telemt_me_route_drop_no_conn_total 233480
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 326497
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 356
telemt_desync_full_logged_total 159
telemt_desync_suppressed_total 197
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 105
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 7173
telemt_me_writer_restored_same_endpoint_total 7056
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 248434
telemt_user_connections_current{user="hello"} 734
telemt_user_octets_from_client{user="hello"} 3586382724 (3.34 GB)
telemt_user_octets_to_client{user="hello"} 160708198024 (149.67 GB)
telemt_user_unique_ips_current{user="hello"} 242
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 33536.9 (9h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1530
telemt_connections_bad_total 193
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 16799
telemt_upstream_connect_success_total 16798
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 16799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9550
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7240
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 15126
telemt_me_reconnect_success_total 15039
telemt_me_reader_eof_total 16466
telemt_me_idle_close_by_peer_total 16466
telemt_me_route_drop_no_conn_total 191
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1320
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 15174
telemt_me_writer_restored_same_endpoint_total 15039
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 1320
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 212100924 (202.28 MB)
telemt_user_octets_to_client{user="hello"} 14374519708 (13.39 GB)
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```