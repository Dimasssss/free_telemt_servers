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

# Server Metrics 2026-03-17 05:33:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 38898.3 (10h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 215486
telemt_connections_bad_total 3213
telemt_handshake_timeouts_total 7314
telemt_upstream_connect_attempt_total 8234
telemt_upstream_connect_success_total 8191
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 8234
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3733
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4453
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6260
telemt_me_reconnect_success_total 6237
telemt_me_reader_eof_total 6639
telemt_me_idle_close_by_peer_total 6639
telemt_me_route_drop_no_conn_total 67444
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 194081
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1257
telemt_desync_full_logged_total 437
telemt_desync_suppressed_total 820
telemt_desync_frames_bucket_total{bucket="1_2"} 295
telemt_desync_frames_bucket_total{bucket="3_10"} 628
telemt_desync_frames_bucket_total{bucket="gt_10"} 334
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 6298
telemt_me_writer_restored_same_endpoint_total 6216
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 193878
telemt_user_connections_current{user="hello"} 597
telemt_user_octets_from_client{user="hello"} 2686776968 (2.50 GB)
telemt_user_octets_to_client{user="hello"} 87871313676 (81.84 GB)
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 39149.4 (10h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125430
telemt_connections_bad_total 2195
telemt_handshake_timeouts_total 10108
telemt_upstream_connect_attempt_total 10844
telemt_upstream_connect_success_total 10704
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 10844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_reconnect_attempts_total 9934
telemt_me_reconnect_success_total 8761
telemt_me_reader_eof_total 9263
telemt_me_idle_close_by_peer_total 9263
telemt_me_route_drop_no_conn_total 48083
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 108463
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 308
telemt_desync_full_logged_total 109
telemt_desync_suppressed_total 199
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 151
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 8878
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 8745
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 108475
telemt_user_connections_current{user="hello"} 250
telemt_user_octets_from_client{user="hello"} 1389321464 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 46646578760 (43.44 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 38925.9 (10h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75513
telemt_connections_bad_total 1091
telemt_handshake_timeouts_total 2554
telemt_upstream_connect_attempt_total 10460
telemt_upstream_connect_success_total 10405
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 10460
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4626
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5717
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 8479
telemt_me_reconnect_success_total 8433
telemt_me_reader_eof_total 9025
telemt_me_idle_close_by_peer_total 9025
telemt_me_route_drop_no_conn_total 25189
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 64593
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 45
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 8536
telemt_me_writer_restored_same_endpoint_total 8422
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 64577
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 5957002860 (5.55 GB)
telemt_user_octets_to_client{user="hello"} 20960323368 (19.52 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 38984.9 (10h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125960
telemt_connections_bad_total 3723
telemt_handshake_timeouts_total 3660
telemt_upstream_connect_attempt_total 8882
telemt_upstream_connect_success_total 8806
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 8882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4633
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_reconnect_attempts_total 6850
telemt_me_reconnect_success_total 6797
telemt_me_reader_eof_total 7243
telemt_me_idle_close_by_peer_total 7243
telemt_me_route_drop_no_conn_total 42667
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 114853
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 224
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6898
telemt_me_writer_restored_same_endpoint_total 6790
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 114871
telemt_user_connections_current{user="hello"} 338
telemt_user_octets_from_client{user="hello"} 1265800086 (1.18 GB)
telemt_user_octets_to_client{user="hello"} 54819459605 (51.05 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 38957.5 (10h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96737
telemt_connections_bad_total 27154
telemt_handshake_timeouts_total 1945
telemt_upstream_connect_attempt_total 11588
telemt_upstream_connect_success_total 11433
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 11588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6127
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 177
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_reconnect_attempts_total 11627
telemt_me_reconnect_success_total 9367
telemt_me_reader_eof_total 9893
telemt_me_idle_close_by_peer_total 9893
telemt_me_route_drop_no_conn_total 25622
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 65051
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 9560
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 9359
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 193
telemt_user_connections_total{user="hello"} 65149
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 727731667 (694.02 MB)
telemt_user_octets_to_client{user="hello"} 28260877534 (26.32 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 39117.9 (10h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 234779
telemt_connections_bad_total 29608
telemt_handshake_timeouts_total 1766
telemt_upstream_connect_attempt_total 8041
telemt_upstream_connect_success_total 7999
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 8041
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3821
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4170
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 6075
telemt_me_reconnect_success_total 6048
telemt_me_reader_eof_total 6490
telemt_me_idle_close_by_peer_total 6490
telemt_me_route_drop_no_conn_total 201101
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 273190
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 236
telemt_desync_full_logged_total 119
telemt_desync_suppressed_total 117
telemt_desync_frames_bucket_total{bucket="1_2"} 78
telemt_desync_frames_bucket_total{bucket="3_10"} 83
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 6137
telemt_me_writer_restored_same_endpoint_total 6038
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 195443
telemt_user_connections_current{user="hello"} 564
telemt_user_octets_from_client{user="hello"} 3037856608 (2.83 GB)
telemt_user_octets_to_client{user="hello"} 146560140500 (136.49 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 27124.3 (7h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 546
telemt_connections_bad_total 190
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 13550
telemt_upstream_connect_success_total 13549
telemt_upstream_connect_attempts_per_request{bucket="1"} 13549
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5734
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 12182
telemt_me_reconnect_success_total 12115
telemt_me_reader_eof_total 13298
telemt_me_idle_close_by_peer_total 13298
telemt_me_route_drop_no_conn_total 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 351
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 12228
telemt_me_writer_restored_same_endpoint_total 12115
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 351
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 160149144 (152.73 MB)
telemt_user_octets_to_client{user="hello"} 245117976 (233.76 MB)
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```