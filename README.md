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

# Server Metrics 2026-03-17 09:48:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 54170.9 (15h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 431121
telemt_connections_bad_total 3675
telemt_handshake_timeouts_total 12350
telemt_upstream_connect_attempt_total 13798
telemt_upstream_connect_success_total 13366
telemt_upstream_connect_fail_total 432
telemt_upstream_connect_attempts_per_request{bucket="1"} 13798
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7119
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6097
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 432
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 9882
telemt_me_reconnect_success_total 8356
telemt_me_reader_eof_total 8885
telemt_me_idle_close_by_peer_total 8884
telemt_me_route_drop_no_conn_total 135860
telemt_me_route_drop_channel_closed_total 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 388996
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3144
telemt_desync_full_logged_total 847
telemt_desync_suppressed_total 2297
telemt_desync_frames_bucket_total{bucket="1_2"} 799
telemt_desync_frames_bucket_total{bucket="3_10"} 1379
telemt_desync_frames_bucket_total{bucket="gt_10"} 966
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 8528
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 8334
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 390974
telemt_user_connections_current{user="hello"} 925
telemt_user_octets_from_client{user="hello"} 5588918675 (5.21 GB)
telemt_user_octets_to_client{user="hello"} 154946611119 (144.31 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 315
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 54422.5 (15h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 234916
telemt_connections_bad_total 2556
telemt_handshake_timeouts_total 13685
telemt_upstream_connect_attempt_total 14161
telemt_upstream_connect_success_total 13965
telemt_upstream_connect_fail_total 196
telemt_upstream_connect_attempts_per_request{bucket="1"} 14161
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6009
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7806
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 196
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 19972
telemt_me_reconnect_success_total 11264
telemt_me_reader_eof_total 12098
telemt_me_idle_close_by_peer_total 12098
telemt_me_route_drop_no_conn_total 85453
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 206755
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 551
telemt_desync_full_logged_total 206
telemt_desync_suppressed_total 345
telemt_desync_frames_bucket_total{bucket="1_2"} 162
telemt_desync_frames_bucket_total{bucket="3_10"} 241
telemt_desync_frames_bucket_total{bucket="gt_10"} 148
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 11650
telemt_me_refill_failed_total 271
telemt_me_writer_restored_same_endpoint_total 11248
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 386
telemt_user_connections_total{user="hello"} 206758
telemt_user_connections_current{user="hello"} 508
telemt_user_octets_from_client{user="hello"} 2522705716 (2.35 GB)
telemt_user_octets_to_client{user="hello"} 79526803144 (74.07 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 54199.0 (15h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144123
telemt_connections_bad_total 7579
telemt_handshake_timeouts_total 10102
telemt_upstream_connect_attempt_total 14450
telemt_upstream_connect_success_total 14374
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 14450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7935
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 12595
telemt_me_reconnect_success_total 11627
telemt_me_reader_eof_total 12424
telemt_me_idle_close_by_peer_total 12424
telemt_me_route_drop_no_conn_total 43690
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 117027
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 365
telemt_desync_full_logged_total 95
telemt_desync_suppressed_total 270
telemt_desync_frames_bucket_total{bucket="1_2"} 136
telemt_desync_frames_bucket_total{bucket="3_10"} 156
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 11810
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 11616
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 116949
telemt_user_connections_current{user="hello"} 307
telemt_user_octets_from_client{user="hello"} 8130500856 (7.57 GB)
telemt_user_octets_to_client{user="hello"} 36629449464 (34.11 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 54258.0 (15h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 317764
telemt_connections_bad_total 6191
telemt_handshake_timeouts_total 10967
telemt_upstream_connect_attempt_total 12392
telemt_upstream_connect_success_total 12277
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 12392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5798
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6399
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 10580
telemt_me_reconnect_success_total 9493
telemt_me_reader_eof_total 10084
telemt_me_idle_close_by_peer_total 10084
telemt_me_route_drop_no_conn_total 87850
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 256166
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 553
telemt_desync_full_logged_total 209
telemt_desync_suppressed_total 344
telemt_desync_frames_bucket_total{bucket="1_2"} 130
telemt_desync_frames_bucket_total{bucket="3_10"} 245
telemt_desync_frames_bucket_total{bucket="gt_10"} 178
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 9672
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 9485
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 256123
telemt_user_connections_current{user="hello"} 716
telemt_user_octets_from_client{user="hello"} 2927298202 (2.73 GB)
telemt_user_octets_to_client{user="hello"} 103068370281 (95.99 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 54229.8 (15h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 177321
telemt_connections_bad_total 48523
telemt_handshake_timeouts_total 2787
telemt_upstream_connect_attempt_total 16526
telemt_upstream_connect_success_total 16311
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 16526
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7287
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8817
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 207
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_reconnect_attempts_total 20587
telemt_me_reconnect_success_total 13467
telemt_me_reader_eof_total 14280
telemt_me_idle_close_by_peer_total 14280
telemt_me_route_drop_no_conn_total 46158
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 120624
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 386
telemt_desync_full_logged_total 97
telemt_desync_suppressed_total 289
telemt_desync_frames_bucket_total{bucket="1_2"} 184
telemt_desync_frames_bucket_total{bucket="3_10"} 141
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 13858
telemt_me_refill_failed_total 220
telemt_me_writer_restored_same_endpoint_total 13459
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 391
telemt_user_connections_total{user="hello"} 120651
telemt_user_connections_current{user="hello"} 242
telemt_user_octets_from_client{user="hello"} 1844765903 (1.72 GB)
telemt_user_octets_to_client{user="hello"} 54859069162 (51.09 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 54391.1 (15h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 415661
telemt_connections_bad_total 48160
telemt_handshake_timeouts_total 4276
telemt_upstream_connect_attempt_total 11111
telemt_upstream_connect_success_total 11051
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 11111
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5428
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5603
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 12220
telemt_me_reconnect_success_total 8338
telemt_me_reader_eof_total 9007
telemt_me_idle_close_by_peer_total 9007
telemt_me_route_drop_no_conn_total 275251
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 418682
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 606
telemt_desync_full_logged_total 239
telemt_desync_suppressed_total 367
telemt_desync_frames_bucket_total{bucket="1_2"} 162
telemt_desync_frames_bucket_total{bucket="3_10"} 229
telemt_desync_frames_bucket_total{bucket="gt_10"} 215
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 8588
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 8324
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 250
telemt_user_connections_total{user="hello"} 340563
telemt_user_connections_current{user="hello"} 869
telemt_user_octets_from_client{user="hello"} 4881167240 (4.55 GB)
telemt_user_octets_to_client{user="hello"} 189586878264 (176.57 GB)
telemt_user_unique_ips_current{user="hello"} 288
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 2158.1 (0h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2088
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 764
telemt_upstream_connect_success_total 742
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 441
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 301
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 495
telemt_me_reconnect_success_total 470
telemt_me_reader_eof_total 468
telemt_me_idle_close_by_peer_total 468
telemt_me_route_drop_no_conn_total 724
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1845
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 480
telemt_me_writer_restored_same_endpoint_total 468
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 1951
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 26229621 (25.01 MB)
telemt_user_octets_to_client{user="hello"} 7732867538 (7.20 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 4
```