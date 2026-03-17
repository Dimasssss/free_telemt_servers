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

# Server Metrics 2026-03-17 09:32:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 53254.4 (14h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 416517
telemt_connections_bad_total 3659
telemt_handshake_timeouts_total 12178
telemt_upstream_connect_attempt_total 13604
telemt_upstream_connect_success_total 13172
telemt_upstream_connect_fail_total 432
telemt_upstream_connect_attempts_per_request{bucket="1"} 13604
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7039
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5983
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 432
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 9732
telemt_me_reconnect_success_total 8210
telemt_me_reader_eof_total 8726
telemt_me_idle_close_by_peer_total 8725
telemt_me_route_drop_no_conn_total 131458
telemt_me_route_drop_channel_closed_total 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 375126
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2954
telemt_desync_full_logged_total 813
telemt_desync_suppressed_total 2141
telemt_desync_frames_bucket_total{bucket="1_2"} 709
telemt_desync_frames_bucket_total{bucket="3_10"} 1330
telemt_desync_frames_bucket_total{bucket="gt_10"} 915
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 8377
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 8188
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 377116
telemt_user_connections_current{user="hello"} 922
telemt_user_octets_from_client{user="hello"} 5428120627 (5.06 GB)
telemt_user_octets_to_client{user="hello"} 151355180855 (140.96 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 315
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 53507.4 (14h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 226304
telemt_connections_bad_total 2473
telemt_handshake_timeouts_total 12978
telemt_upstream_connect_attempt_total 14080
telemt_upstream_connect_success_total 13890
telemt_upstream_connect_fail_total 190
telemt_upstream_connect_attempts_per_request{bucket="1"} 14080
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7778
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 190
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 18597
telemt_me_reconnect_success_total 11233
telemt_me_reader_eof_total 12025
telemt_me_idle_close_by_peer_total 12025
telemt_me_route_drop_no_conn_total 82854
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 199518
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 536
telemt_desync_full_logged_total 196
telemt_desync_suppressed_total 340
telemt_desync_frames_bucket_total{bucket="1_2"} 161
telemt_desync_frames_bucket_total{bucket="3_10"} 231
telemt_desync_frames_bucket_total{bucket="gt_10"} 144
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 11576
telemt_me_refill_failed_total 229
telemt_me_writer_restored_same_endpoint_total 11217
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 343
telemt_user_connections_total{user="hello"} 199520
telemt_user_connections_current{user="hello"} 454
telemt_user_octets_from_client{user="hello"} 2440638420 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 77848344648 (72.50 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 53283.4 (14h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139425
telemt_connections_bad_total 7577
telemt_handshake_timeouts_total 9470
telemt_upstream_connect_attempt_total 14251
telemt_upstream_connect_success_total 14176
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 14251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6266
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7845
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 12442
telemt_me_reconnect_success_total 11476
telemt_me_reader_eof_total 12265
telemt_me_idle_close_by_peer_total 12265
telemt_me_route_drop_no_conn_total 42463
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 113073
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 340
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 251
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 144
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 11654
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 11465
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 112995
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 7521354880 (7.00 GB)
telemt_user_octets_to_client{user="hello"} 35178701092 (32.76 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 53342.1 (14h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 305847
telemt_connections_bad_total 6189
telemt_handshake_timeouts_total 10816
telemt_upstream_connect_attempt_total 12141
telemt_upstream_connect_success_total 12030
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 12141
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5675
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6280
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 10374
telemt_me_reconnect_success_total 9291
telemt_me_reader_eof_total 9884
telemt_me_idle_close_by_peer_total 9884
telemt_me_route_drop_no_conn_total 84391
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 245227
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 526
telemt_desync_full_logged_total 198
telemt_desync_suppressed_total 328
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 231
telemt_desync_frames_bucket_total{bucket="gt_10"} 171
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 9469
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 9283
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 245188
telemt_user_connections_current{user="hello"} 729
telemt_user_octets_from_client{user="hello"} 2635616862 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 99527378585 (92.69 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 53314.0 (14h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 171643
telemt_connections_bad_total 46783
telemt_handshake_timeouts_total 2767
telemt_upstream_connect_attempt_total 16296
telemt_upstream_connect_success_total 16083
telemt_upstream_connect_fail_total 213
telemt_upstream_connect_attempts_per_request{bucket="1"} 16296
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8688
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 202
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 213
telemt_me_reconnect_attempts_total 20404
telemt_me_reconnect_success_total 13289
telemt_me_reader_eof_total 14100
telemt_me_idle_close_by_peer_total 14100
telemt_me_route_drop_no_conn_total 44714
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 116841
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 368
telemt_desync_full_logged_total 94
telemt_desync_suppressed_total 274
telemt_desync_frames_bucket_total{bucket="1_2"} 173
telemt_desync_frames_bucket_total{bucket="3_10"} 136
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 13677
telemt_me_refill_failed_total 220
telemt_me_writer_restored_same_endpoint_total 13281
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 388
telemt_user_connections_total{user="hello"} 116869
telemt_user_connections_current{user="hello"} 264
telemt_user_octets_from_client{user="hello"} 1805911547 (1.68 GB)
telemt_user_octets_to_client{user="hello"} 52749433866 (49.13 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 53475.8 (14h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 405022
telemt_connections_bad_total 47826
telemt_handshake_timeouts_total 4009
telemt_upstream_connect_attempt_total 10946
telemt_upstream_connect_success_total 10887
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 10946
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5528
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 12099
telemt_me_reconnect_success_total 8219
telemt_me_reader_eof_total 8877
telemt_me_idle_close_by_peer_total 8877
telemt_me_route_drop_no_conn_total 270579
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 409025
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 578
telemt_desync_full_logged_total 232
telemt_desync_suppressed_total 346
telemt_desync_frames_bucket_total{bucket="1_2"} 153
telemt_desync_frames_bucket_total{bucket="3_10"} 220
telemt_desync_frames_bucket_total{bucket="gt_10"} 205
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 8466
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 8205
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 330917
telemt_user_connections_current{user="hello"} 831
telemt_user_octets_from_client{user="hello"} 4757786712 (4.43 GB)
telemt_user_octets_to_client{user="hello"} 183319095384 (170.73 GB)
telemt_user_unique_ips_current{user="hello"} 279
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 1242.1 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1209
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 352
telemt_upstream_connect_success_total 332
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 233
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_reconnect_attempts_total 129
telemt_me_reconnect_success_total 109
telemt_me_reader_eof_total 105
telemt_me_idle_close_by_peer_total 105
telemt_me_route_drop_no_conn_total 284
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1014
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 117
telemt_me_writer_restored_same_endpoint_total 107
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 1120
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 17353893 (16.55 MB)
telemt_user_octets_to_client{user="hello"} 5019422118 (4.67 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 7
```