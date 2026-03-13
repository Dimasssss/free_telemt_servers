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

# Server Metrics 2026-03-13 18:23:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 125432.9 (34h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 530223
telemt_connections_bad_total 10053
telemt_handshake_timeouts_total 12169
telemt_upstream_connect_attempt_total 31522
telemt_upstream_connect_success_total 31367
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 31522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16994
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3484
telemt_me_reconnect_attempts_total 29724
telemt_me_reconnect_success_total 25082
telemt_me_reader_eof_total 26790
telemt_me_idle_close_by_peer_total 26789
telemt_me_route_drop_no_conn_total 173305
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 459868
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1471
telemt_desync_full_logged_total 510
telemt_desync_suppressed_total 961
telemt_desync_frames_bucket_total{bucket="1_2"} 323
telemt_desync_frames_bucket_total{bucket="3_10"} 541
telemt_desync_frames_bucket_total{bucket="gt_10"} 607
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 25504
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 25066
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 422
telemt_user_connections_total{user="hello"} 459437
telemt_user_connections_current{user="hello"} 319
telemt_user_octets_from_client{user="hello"} 8445435768 (7.87 GB)
telemt_user_octets_to_client{user="hello"} 218023219640 (203.05 GB)
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 125326.0 (34h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 262564
telemt_connections_bad_total 1953
telemt_handshake_timeouts_total 1839
telemt_upstream_connect_attempt_total 115218
telemt_upstream_connect_success_total 114360
telemt_upstream_connect_fail_total 858
telemt_upstream_connect_attempts_per_request{bucket="1"} 115218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 85880
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26782
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1698
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 858
telemt_me_keepalive_timeout_total 1530
telemt_me_reconnect_attempts_total 130048
telemt_me_reconnect_success_total 26033
telemt_me_reader_eof_total 30037
telemt_me_idle_close_by_peer_total 30037
telemt_me_route_drop_no_conn_total 83016
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 166881
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 29507
telemt_me_refill_failed_total 3246
telemt_me_writer_restored_same_endpoint_total 26016
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3474
telemt_user_connections_total{user="hello"} 248725
telemt_user_connections_current{user="hello"} 208
telemt_user_octets_from_client{user="hello"} 2588902262 (2.41 GB)
telemt_user_octets_to_client{user="hello"} 76323643295 (71.08 GB)
telemt_user_msgs_from_client{user="hello"} 1292024
telemt_user_msgs_to_client{user="hello"} 7474550
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 125289.6 (34h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 310158
telemt_connections_bad_total 2628
telemt_handshake_timeouts_total 19261
telemt_upstream_connect_attempt_total 33394
telemt_upstream_connect_success_total 33390
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 33394
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15472
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17879
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2700
telemt_me_reconnect_attempts_total 28304
telemt_me_reconnect_success_total 27073
telemt_me_reader_eof_total 29039
telemt_me_idle_close_by_peer_total 29039
telemt_me_route_drop_no_conn_total 110637
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 277413
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 104
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 115
telemt_me_writer_removed_unexpected_total 27376
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 27053
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 303
telemt_user_connections_total{user="hello"} 277320
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 10309304760 (9.60 GB)
telemt_user_octets_to_client{user="hello"} 114077294664 (106.24 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 125265.1 (34h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 415695
telemt_connections_bad_total 15129
telemt_handshake_timeouts_total 3887
telemt_upstream_connect_attempt_total 60760
telemt_upstream_connect_success_total 50500
telemt_upstream_connect_fail_total 10260
telemt_upstream_connect_attempts_per_request{bucket="1"} 60760
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31982
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18221
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 288
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10260
telemt_me_keepalive_timeout_total 4676
telemt_me_reconnect_attempts_total 114852
telemt_me_reconnect_success_total 25193
telemt_me_reader_eof_total 28725
telemt_me_idle_close_by_peer_total 28718
telemt_me_route_drop_no_conn_total 143355
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 347634
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1360
telemt_desync_full_logged_total 405
telemt_desync_suppressed_total 955
telemt_desync_frames_bucket_total{bucket="1_2"} 334
telemt_desync_frames_bucket_total{bucket="3_10"} 524
telemt_desync_frames_bucket_total{bucket="gt_10"} 502
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 28316
telemt_me_refill_failed_total 2796
telemt_me_writer_restored_same_endpoint_total 25183
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3123
telemt_user_connections_total{user="hello"} 366515
telemt_user_connections_current{user="hello"} 218
telemt_user_octets_from_client{user="hello"} 8398960147 (7.82 GB)
telemt_user_octets_to_client{user="hello"} 130470268272 (121.51 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 75436.5 (20h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125295
telemt_connections_bad_total 15617
telemt_handshake_timeouts_total 1404
telemt_upstream_connect_attempt_total 29518
telemt_upstream_connect_success_total 29241
telemt_upstream_connect_fail_total 276
telemt_upstream_connect_attempts_per_request{bucket="1"} 29517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14040
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 276
telemt_me_keepalive_timeout_total 1200
telemt_me_reconnect_attempts_total 33965
telemt_me_reconnect_success_total 20575
telemt_me_reader_eof_total 22056
telemt_me_idle_close_by_peer_total 22056
telemt_me_route_drop_no_conn_total 39254
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 99326
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 490
telemt_desync_full_logged_total 106
telemt_desync_suppressed_total 384
telemt_desync_frames_bucket_total{bucket="1_2"} 71
telemt_desync_frames_bucket_total{bucket="3_10"} 259
telemt_desync_frames_bucket_total{bucket="gt_10"} 160
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 21185
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 20557
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 610
telemt_user_connections_total{user="hello"} 104223
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 1218514893 (1.13 GB)
telemt_user_octets_to_client{user="hello"} 34917888375 (32.52 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 125221.9 (34h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 766136
telemt_connections_bad_total 24767
telemt_handshake_timeouts_total 24586
telemt_upstream_connect_attempt_total 25996
telemt_upstream_connect_success_total 25858
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 25996
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13712
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_keepalive_timeout_total 3003
telemt_me_reconnect_attempts_total 24265
telemt_me_reconnect_success_total 19622
telemt_me_reader_eof_total 21057
telemt_me_idle_close_by_peer_total 21054
telemt_me_route_drop_no_conn_total 364105
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 718776
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 689
telemt_desync_full_logged_total 224
telemt_desync_suppressed_total 465
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 224
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 116
telemt_me_writer_removed_unexpected_total 20026
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 19615
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 404
telemt_user_connections_total{user="hello"} 691663
telemt_user_connections_current{user="hello"} 556
telemt_user_octets_from_client{user="hello"} 12096230768 (11.27 GB)
telemt_user_octets_to_client{user="hello"} 343254925520 (319.68 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 75
```