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

# Server Metrics 2026-03-17 08:21:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 48974.9 (13h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 345833
telemt_connections_bad_total 3573
telemt_handshake_timeouts_total 10053
telemt_upstream_connect_attempt_total 10126
telemt_upstream_connect_success_total 10071
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 10126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4637
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5428
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 8808
telemt_me_reconnect_success_total 7625
telemt_me_reader_eof_total 8132
telemt_me_idle_close_by_peer_total 8132
telemt_me_route_drop_no_conn_total 106587
telemt_me_route_drop_channel_closed_total 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 313072
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2426
telemt_desync_full_logged_total 684
telemt_desync_suppressed_total 1742
telemt_desync_frames_bucket_total{bucket="1_2"} 567
telemt_desync_frames_bucket_total{bucket="3_10"} 1158
telemt_desync_frames_bucket_total{bucket="gt_10"} 701
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 7742
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 7604
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 312807
telemt_user_connections_current{user="hello"} 779
telemt_user_octets_from_client{user="hello"} 4337871656 (4.04 GB)
telemt_user_octets_to_client{user="hello"} 130480743288 (121.52 GB)
telemt_user_unique_ips_current{user="hello"} 296
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 49226.2 (13h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 192801
telemt_connections_bad_total 2351
telemt_handshake_timeouts_total 12054
telemt_upstream_connect_attempt_total 13381
telemt_upstream_connect_success_total 13206
telemt_upstream_connect_fail_total 175
telemt_upstream_connect_attempts_per_request{bucket="1"} 13381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7462
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 175
telemt_me_reconnect_attempts_total 13045
telemt_me_reconnect_success_total 10772
telemt_me_reader_eof_total 11398
telemt_me_idle_close_by_peer_total 11398
telemt_me_route_drop_no_conn_total 70236
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168677
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 425
telemt_desync_full_logged_total 155
telemt_desync_suppressed_total 270
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 183
telemt_desync_frames_bucket_total{bucket="gt_10"} 115
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 10947
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 10756
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 175
telemt_user_connections_total{user="hello"} 168691
telemt_user_connections_current{user="hello"} 538
telemt_user_octets_from_client{user="hello"} 2066168904 (1.92 GB)
telemt_user_octets_to_client{user="hello"} 66719587312 (62.14 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 49002.3 (13h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119360
telemt_connections_bad_total 7514
telemt_handshake_timeouts_total 6009
telemt_upstream_connect_attempt_total 12887
telemt_upstream_connect_success_total 12820
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 12887
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5672
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7086
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 10412
telemt_me_reconnect_success_total 10348
telemt_me_reader_eof_total 11060
telemt_me_idle_close_by_peer_total 11060
telemt_me_route_drop_no_conn_total 37111
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 96927
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 238
telemt_desync_full_logged_total 58
telemt_desync_suppressed_total 180
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 10481
telemt_me_writer_restored_same_endpoint_total 10337
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 96872
telemt_user_connections_current{user="hello"} 259
telemt_user_octets_from_client{user="hello"} 6561219584 (6.11 GB)
telemt_user_octets_to_client{user="hello"} 31174819400 (29.03 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 49061.3 (13h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 256419
telemt_connections_bad_total 6155
telemt_handshake_timeouts_total 10398
telemt_upstream_connect_attempt_total 11246
telemt_upstream_connect_success_total 11151
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 11246
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5270
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5812
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 9710
telemt_me_reconnect_success_total 8644
telemt_me_reader_eof_total 9204
telemt_me_idle_close_by_peer_total 9204
telemt_me_route_drop_no_conn_total 68804
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 198591
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 428
telemt_desync_full_logged_total 153
telemt_desync_suppressed_total 275
telemt_desync_frames_bucket_total{bucket="1_2"} 109
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 142
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 8802
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 8636
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 198587
telemt_user_connections_current{user="hello"} 658
telemt_user_octets_from_client{user="hello"} 2118955974 (1.97 GB)
telemt_user_octets_to_client{user="hello"} 87871823601 (81.84 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 49033.2 (13h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145000
telemt_connections_bad_total 39222
telemt_handshake_timeouts_total 2623
telemt_upstream_connect_attempt_total 15111
telemt_upstream_connect_success_total 14908
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 15111
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6662
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8053
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_reconnect_attempts_total 18203
telemt_me_reconnect_success_total 12345
telemt_me_reader_eof_total 13073
telemt_me_idle_close_by_peer_total 13073
telemt_me_route_drop_no_conn_total 38365
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 98582
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 253
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 191
telemt_desync_frames_bucket_total{bucket="1_2"} 116
telemt_desync_frames_bucket_total{bucket="3_10"} 91
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 12677
telemt_me_refill_failed_total 181
telemt_me_writer_restored_same_endpoint_total 12337
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 332
telemt_user_connections_total{user="hello"} 98619
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 1436004595 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 46625865250 (43.42 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 49194.5 (13h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 352875
telemt_connections_bad_total 45469
telemt_handshake_timeouts_total 3512
telemt_upstream_connect_attempt_total 10138
telemt_upstream_connect_success_total 10083
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 10138
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4914
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5154
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 11513
telemt_me_reconnect_success_total 7637
telemt_me_reader_eof_total 8256
telemt_me_idle_close_by_peer_total 8256
telemt_me_route_drop_no_conn_total 250737
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 363178
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 450
telemt_desync_full_logged_total 180
telemt_desync_suppressed_total 270
telemt_desync_frames_bucket_total{bucket="1_2"} 141
telemt_desync_frames_bucket_total{bucket="3_10"} 165
telemt_desync_frames_bucket_total{bucket="gt_10"} 144
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 7867
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 7623
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 230
telemt_user_connections_total{user="hello"} 285093
telemt_user_connections_current{user="hello"} 751
telemt_user_octets_from_client{user="hello"} 4018471272 (3.74 GB)
telemt_user_octets_to_client{user="hello"} 169629589668 (157.98 GB)
telemt_user_unique_ips_current{user="hello"} 251
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 37200.8 (10h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2671
telemt_connections_bad_total 203
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 18276
telemt_upstream_connect_success_total 18275
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 18276
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7961
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 16428
telemt_me_reconnect_success_total 16334
telemt_me_reader_eof_total 17881
telemt_me_idle_close_by_peer_total 17881
telemt_me_route_drop_no_conn_total 491
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2434
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 16480
telemt_me_writer_restored_same_endpoint_total 16334
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 2434
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 708911412 (676.07 MB)
telemt_user_octets_to_client{user="hello"} 17775010760 (16.55 GB)
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 5
```