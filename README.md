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

# Server Metrics 2026-03-19 13:18:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 2193.6 (0h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98615
telemt_connections_bad_total 3846
telemt_connections_current 1619
telemt_connections_me_current 1619
telemt_handshake_timeouts_total 1987
telemt_upstream_connect_attempt_total 323
telemt_upstream_connect_success_total 302
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 144
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 158
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 160
telemt_me_reconnect_success_total 144
telemt_me_reader_eof_total 138
telemt_me_idle_close_by_peer_total 138
telemt_me_route_drop_no_conn_total 83764
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87491
telemt_me_writer_pick_total{mode="p2c",result="full"} 54
telemt_me_writer_pick_total{mode="p2c",result="closed"} 152
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 359
telemt_desync_full_logged_total 120
telemt_desync_suppressed_total 239
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 166
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 25
telemt_me_writer_removed_unexpected_total 158
telemt_me_writer_restored_same_endpoint_total 133
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 220
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 87077
telemt_user_connections_current{user="hello"} 1619
telemt_user_octets_from_client{user="hello"} 1293223368 (1.20 GB)
telemt_user_octets_to_client{user="hello"} 23837561032 (22.20 GB)
telemt_user_unique_ips_current{user="hello"} 566
telemt_user_unique_ips_recent_window{user="hello"} 244
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 2103.6 (0h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 264839
telemt_connections_bad_total 6608
telemt_connections_current 3730
telemt_connections_me_current 3730
telemt_handshake_timeouts_total 2740
telemt_upstream_connect_attempt_total 1827
telemt_upstream_connect_success_total 1816
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1827
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1550
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 264
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 862
telemt_me_reconnect_success_total 439
telemt_me_reader_eof_total 400
telemt_me_idle_close_by_peer_total 400
telemt_me_route_drop_no_conn_total 271646
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 236597
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 684
telemt_desync_full_logged_total 213
telemt_desync_suppressed_total 471
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 268
telemt_desync_frames_bucket_total{bucket="gt_10"} 294
telemt_me_writer_close_signal_drop_total 25
telemt_me_writer_removed_unexpected_total 425
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 384
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_user_connections_total{user="hello"} 237455
telemt_user_connections_current{user="hello"} 3730
telemt_user_octets_from_client{user="hello"} 3479704298 (3.24 GB)
telemt_user_octets_to_client{user="hello"} 52695861790 (49.08 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1267
telemt_user_unique_ips_recent_window{user="hello"} 547
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 2081.5 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 262829
telemt_connections_bad_total 21163
telemt_connections_current 3095
telemt_connections_me_current 3095
telemt_handshake_timeouts_total 3264
telemt_upstream_connect_attempt_total 370
telemt_upstream_connect_success_total 367
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 133
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 1107
telemt_me_reconnect_success_total 211
telemt_me_reader_eof_total 132
telemt_me_idle_close_by_peer_total 132
telemt_me_route_drop_no_conn_total 178251
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 189017
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 731
telemt_desync_full_logged_total 161
telemt_desync_suppressed_total 570
telemt_desync_frames_bucket_total{bucket="1_2"} 230
telemt_desync_frames_bucket_total{bucket="3_10"} 250
telemt_desync_frames_bucket_total{bucket="gt_10"} 251
telemt_pool_swap_total 1
telemt_me_writer_close_signal_drop_total 25
telemt_me_writer_removed_unexpected_total 156
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 210
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 188655
telemt_user_connections_current{user="hello"} 3095
telemt_user_octets_from_client{user="hello"} 1404696660 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 50160392116 (46.72 GB)
telemt_user_unique_ips_current{user="hello"} 1071
telemt_user_unique_ips_recent_window{user="hello"} 488
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 2069.0 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207676
telemt_connections_bad_total 26940
telemt_connections_current 2943
telemt_connections_me_current 2943
telemt_handshake_timeouts_total 2365
telemt_upstream_connect_attempt_total 394
telemt_upstream_connect_success_total 380
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 394
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 184
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 233
telemt_me_reconnect_success_total 225
telemt_me_reader_eof_total 186
telemt_me_idle_close_by_peer_total 186
telemt_me_route_drop_no_conn_total 127227
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 163601
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 501
telemt_desync_full_logged_total 166
telemt_desync_suppressed_total 335
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 228
telemt_pool_swap_total 1
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 207
telemt_me_writer_restored_same_endpoint_total 222
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 402
telemt_user_connections_total{user="hello"} 163426
telemt_user_connections_current{user="hello"} 2943
telemt_user_octets_from_client{user="hello"} 1838777932 (1.71 GB)
telemt_user_octets_to_client{user="hello"} 33940179296 (31.61 GB)
telemt_user_unique_ips_current{user="hello"} 1000
telemt_user_unique_ips_recent_window{user="hello"} 471
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 55792.3 (15h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3757507
telemt_connections_bad_total 743861
telemt_connections_current 3640
telemt_connections_me_current 3640
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 74190
telemt_upstream_connect_attempt_total 61702
telemt_upstream_connect_success_total 59221
telemt_upstream_connect_fail_total 2481
telemt_upstream_connect_attempts_per_request{bucket="1"} 61702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6912
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1014
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2481
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 70321
telemt_me_reconnect_success_total 7269
telemt_me_reader_eof_total 7593
telemt_me_idle_close_by_peer_total 7590
telemt_me_route_drop_no_conn_total 1667029
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2524898
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10961
telemt_desync_full_logged_total 3386
telemt_desync_suppressed_total 7575
telemt_desync_frames_bucket_total{bucket="1_2"} 1953
telemt_desync_frames_bucket_total{bucket="3_10"} 4680
telemt_desync_frames_bucket_total{bucket="gt_10"} 4328
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 7392
telemt_me_refill_failed_total 1967
telemt_me_writer_restored_same_endpoint_total 7245
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 2573719
telemt_user_connections_current{user="hello"} 3640
telemt_user_octets_from_client{user="hello"} 40964382487 (38.15 GB)
telemt_user_octets_to_client{user="hello"} 936505647224 (872.19 GB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1181
telemt_user_unique_ips_recent_window{user="hello"} 558
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 2033.7 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55487
telemt_connections_bad_total 1737
telemt_connections_current 936
telemt_connections_me_current 936
telemt_handshake_timeouts_total 2594
telemt_upstream_connect_attempt_total 358
telemt_upstream_connect_success_total 358
telemt_upstream_connect_attempts_per_request{bucket="1"} 358
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 221
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 136
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_me_reconnect_attempts_total 204
telemt_me_reconnect_success_total 199
telemt_me_reader_eof_total 142
telemt_me_idle_close_by_peer_total 142
telemt_me_route_drop_no_conn_total 53702
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48660
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 464
telemt_me_writer_pick_total{mode="p2c",result="full"} 2833
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_writer_pick_blocking_fallback_total 3285
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 89
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 53
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_pool_swap_total 1
telemt_me_writer_close_signal_drop_total 26
telemt_me_writer_removed_unexpected_total 162
telemt_me_writer_restored_same_endpoint_total 190
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 145
telemt_me_async_recovery_trigger_total 928
telemt_user_connections_total{user="hello"} 49223
telemt_user_connections_current{user="hello"} 936
telemt_user_octets_from_client{user="hello"} 738380572 (704.17 MB)
telemt_user_octets_to_client{user="hello"} 9538518984 (8.88 GB)
telemt_user_unique_ips_current{user="hello"} 344
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 2033.7 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145372
telemt_connections_bad_total 11173
telemt_connections_current 3347
telemt_connections_me_current 3347
telemt_handshake_timeouts_total 1823
telemt_upstream_connect_attempt_total 337
telemt_upstream_connect_success_total 334
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 337
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 182
telemt_me_reconnect_success_total 177
telemt_me_reader_eof_total 165
telemt_me_idle_close_by_peer_total 165
telemt_me_route_drop_no_conn_total 45106
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 126967
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 570
telemt_desync_full_logged_total 172
telemt_desync_suppressed_total 398
telemt_desync_frames_bucket_total{bucket="1_2"} 82
telemt_desync_frames_bucket_total{bucket="3_10"} 209
telemt_desync_frames_bucket_total{bucket="gt_10"} 279
telemt_pool_swap_total 1
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 181
telemt_me_writer_restored_same_endpoint_total 160
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 126944
telemt_user_connections_current{user="hello"} 3347
telemt_user_octets_from_client{user="hello"} 1526862228 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 52375716228 (48.78 GB)
telemt_user_unique_ips_current{user="hello"} 1074
telemt_user_unique_ips_recent_window{user="hello"} 426
```