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

# Server Metrics 2026-03-15 20:50:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 81367.8 (22h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 380401
telemt_connections_bad_total 4971
telemt_handshake_timeouts_total 13721
telemt_upstream_connect_attempt_total 19449
telemt_upstream_connect_success_total 19352
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 19449
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8557
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10749
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 18696
telemt_me_reconnect_success_total 15293
telemt_me_reader_eof_total 16305
telemt_me_idle_close_by_peer_total 16305
telemt_me_route_drop_no_conn_total 480082
telemt_me_route_drop_channel_closed_total 78
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 408298
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2012
telemt_desync_full_logged_total 789
telemt_desync_suppressed_total 1223
telemt_desync_frames_bucket_total{bucket="1_2"} 377
telemt_desync_frames_bucket_total{bucket="3_10"} 785
telemt_desync_frames_bucket_total{bucket="gt_10"} 850
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 15567
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 15259
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 274
telemt_user_connections_total{user="hello"} 347360
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 7774044276 (7.24 GB)
telemt_user_octets_to_client{user="hello"} 264081449032 (245.95 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 81374.1 (22h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 157261
telemt_connections_bad_total 2863
telemt_handshake_timeouts_total 13776
telemt_upstream_connect_attempt_total 22386
telemt_upstream_connect_success_total 22312
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 22386
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9671
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12041
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 600
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 1305
telemt_me_reconnect_attempts_total 23382
telemt_me_reconnect_success_total 17846
telemt_me_reader_eof_total 19053
telemt_me_idle_close_by_peer_total 19052
telemt_me_route_drop_no_conn_total 64841
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 134058
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 18290
telemt_me_refill_failed_total 166
telemt_me_writer_restored_same_endpoint_total 17830
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 444
telemt_user_connections_total{user="hello"} 134328
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 2462177117 (2.29 GB)
telemt_user_octets_to_client{user="hello"} 68037314908 (63.36 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 81366.6 (22h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156327
telemt_connections_bad_total 1734
telemt_handshake_timeouts_total 3395
telemt_upstream_connect_attempt_total 23346
telemt_upstream_connect_success_total 23338
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 23346
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10144
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13147
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 26589
telemt_me_reconnect_success_total 19223
telemt_me_reader_eof_total 20652
telemt_me_idle_close_by_peer_total 20651
telemt_me_route_drop_no_conn_total 62128
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 138822
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 19641
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 19215
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 418
telemt_user_connections_total{user="hello"} 138704
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 10926164304 (10.18 GB)
telemt_user_octets_to_client{user="hello"} 81251200632 (75.67 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 81366.3 (22h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 226239
telemt_connections_bad_total 1182
telemt_handshake_timeouts_total 1578
telemt_upstream_connect_attempt_total 19022
telemt_upstream_connect_success_total 19006
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 19022
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9812
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 15040
telemt_me_reconnect_success_total 14949
telemt_me_reader_eof_total 15928
telemt_me_idle_close_by_peer_total 15928
telemt_me_route_drop_no_conn_total 82817
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 208126
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 779
telemt_desync_full_logged_total 274
telemt_desync_suppressed_total 505
telemt_desync_frames_bucket_total{bucket="1_2"} 153
telemt_desync_frames_bucket_total{bucket="3_10"} 343
telemt_desync_frames_bucket_total{bucket="gt_10"} 283
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 15128
telemt_me_writer_restored_same_endpoint_total 14938
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 208044
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 3849127292 (3.58 GB)
telemt_user_octets_to_client{user="hello"} 94689243488 (88.19 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 56437.8 (15h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137610
telemt_connections_bad_total 26603
telemt_handshake_timeouts_total 2533
telemt_upstream_connect_attempt_total 16430
telemt_upstream_connect_success_total 16330
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 16430
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8804
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 107794
telemt_me_reconnect_success_total 13339
telemt_me_reader_eof_total 14044
telemt_me_idle_close_by_peer_total 14044
telemt_me_route_drop_no_conn_total 45999
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 104645
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 336
telemt_desync_full_logged_total 77
telemt_desync_suppressed_total 259
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 127
telemt_desync_frames_bucket_total{bucket="gt_10"} 158
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 13430
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 13235
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 104773
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 1661249545 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 40393135391 (37.62 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 81365.7 (22h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 550820
telemt_connections_bad_total 58470
telemt_handshake_timeouts_total 4340
telemt_upstream_connect_attempt_total 17280
telemt_upstream_connect_success_total 17183
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 17280
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8909
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 14407
telemt_me_reconnect_success_total 13097
telemt_me_reader_eof_total 13923
telemt_me_idle_close_by_peer_total 13923
telemt_me_route_drop_no_conn_total 408498
telemt_me_route_drop_channel_closed_total 95
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 545483
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 323
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 233
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 13278
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 13070
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 181
telemt_user_connections_total{user="hello"} 467374
telemt_user_connections_current{user="hello"} 462
telemt_user_octets_from_client{user="hello"} 11770717156 (10.96 GB)
telemt_user_octets_to_client{user="hello"} 271665405984 (253.01 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 47
```