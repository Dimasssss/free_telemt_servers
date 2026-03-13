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

# Server Metrics 2026-03-13 18:49:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 126961.4 (35h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 537881
telemt_connections_bad_total 11207
telemt_handshake_timeouts_total 12264
telemt_upstream_connect_attempt_total 32219
telemt_upstream_connect_success_total 32054
telemt_upstream_connect_fail_total 165
telemt_upstream_connect_attempts_per_request{bucket="1"} 32219
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17155
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 165
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4298
telemt_me_reconnect_attempts_total 29966
telemt_me_reconnect_success_total 25318
telemt_me_reader_eof_total 27037
telemt_me_idle_close_by_peer_total 27036
telemt_me_route_drop_no_conn_total 176378
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 465693
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1475
telemt_desync_full_logged_total 511
telemt_desync_suppressed_total 964
telemt_desync_frames_bucket_total{bucket="1_2"} 323
telemt_desync_frames_bucket_total{bucket="3_10"} 543
telemt_desync_frames_bucket_total{bucket="gt_10"} 609
telemt_pool_swap_total 113
telemt_me_writer_removed_unexpected_total 25746
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 25302
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 428
telemt_user_connections_total{user="hello"} 465644
telemt_user_connections_current{user="hello"} 291
telemt_user_octets_from_client{user="hello"} 8534554850 (7.95 GB)
telemt_user_octets_to_client{user="hello"} 220492197156 (205.35 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 126854.3 (35h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 267584
telemt_connections_bad_total 1957
telemt_handshake_timeouts_total 1843
telemt_upstream_connect_attempt_total 119685
telemt_upstream_connect_success_total 118823
telemt_upstream_connect_fail_total 862
telemt_upstream_connect_attempts_per_request{bucket="1"} 119685
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 89759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27206
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1858
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 862
telemt_me_keepalive_timeout_total 1557
telemt_me_reconnect_attempts_total 131459
telemt_me_reconnect_success_total 26035
telemt_me_reader_eof_total 30082
telemt_me_idle_close_by_peer_total 30082
telemt_me_route_drop_no_conn_total 83131
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 167315
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
telemt_me_writer_removed_unexpected_total 29553
telemt_me_refill_failed_total 3290
telemt_me_writer_restored_same_endpoint_total 26018
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3518
telemt_user_connections_total{user="hello"} 253575
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 2627106923 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 77188261689 (71.89 GB)
telemt_user_msgs_from_client{user="hello"} 1359268
telemt_user_msgs_to_client{user="hello"} 7736677
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 126817.7 (35h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 315241
telemt_connections_bad_total 2630
telemt_handshake_timeouts_total 20260
telemt_upstream_connect_attempt_total 33729
telemt_upstream_connect_success_total 33724
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 33729
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15615
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18070
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2747
telemt_me_reconnect_attempts_total 28596
telemt_me_reconnect_success_total 27363
telemt_me_reader_eof_total 29345
telemt_me_idle_close_by_peer_total 29345
telemt_me_route_drop_no_conn_total 112550
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 281312
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 116
telemt_me_writer_removed_unexpected_total 27670
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 27343
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 307
telemt_user_connections_total{user="hello"} 281221
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 10385186152 (9.67 GB)
telemt_user_octets_to_client{user="hello"} 117354862372 (109.30 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 126793.4 (35h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 420102
telemt_connections_bad_total 15145
telemt_handshake_timeouts_total 3889
telemt_upstream_connect_attempt_total 61315
telemt_upstream_connect_success_total 51048
telemt_upstream_connect_fail_total 10267
telemt_upstream_connect_attempts_per_request{bucket="1"} 61315
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18526
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10267
telemt_me_keepalive_timeout_total 4690
telemt_me_reconnect_attempts_total 115357
telemt_me_reconnect_success_total 25697
telemt_me_reader_eof_total 29234
telemt_me_idle_close_by_peer_total 29227
telemt_me_route_drop_no_conn_total 145164
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 351848
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1378
telemt_desync_full_logged_total 414
telemt_desync_suppressed_total 964
telemt_desync_frames_bucket_total{bucket="1_2"} 341
telemt_desync_frames_bucket_total{bucket="3_10"} 526
telemt_desync_frames_bucket_total{bucket="gt_10"} 511
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 28826
telemt_me_refill_failed_total 2796
telemt_me_writer_restored_same_endpoint_total 25687
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3129
telemt_user_connections_total{user="hello"} 370729
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 8427519087 (7.85 GB)
telemt_user_octets_to_client{user="hello"} 131662155828 (122.62 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 76964.9 (21h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128947
telemt_connections_bad_total 15892
telemt_handshake_timeouts_total 1410
telemt_upstream_connect_attempt_total 29897
telemt_upstream_connect_success_total 29615
telemt_upstream_connect_fail_total 281
telemt_upstream_connect_attempts_per_request{bucket="1"} 29896
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14213
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 281
telemt_me_keepalive_timeout_total 1218
telemt_me_reconnect_attempts_total 34251
telemt_me_reconnect_success_total 20860
telemt_me_reader_eof_total 22367
telemt_me_idle_close_by_peer_total 22367
telemt_me_route_drop_no_conn_total 40304
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 102546
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 504
telemt_desync_full_logged_total 115
telemt_desync_suppressed_total 389
telemt_desync_frames_bucket_total{bucket="1_2"} 73
telemt_desync_frames_bucket_total{bucket="3_10"} 267
telemt_desync_frames_bucket_total{bucket="gt_10"} 164
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 21470
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 20842
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 610
telemt_user_connections_total{user="hello"} 107441
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 1241044841 (1.16 GB)
telemt_user_octets_to_client{user="hello"} 37618840199 (35.04 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 126749.6 (35h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 776262
telemt_connections_bad_total 24775
telemt_handshake_timeouts_total 24767
telemt_upstream_connect_attempt_total 26236
telemt_upstream_connect_success_total 26097
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 26236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12208
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13857
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 3022
telemt_me_reconnect_attempts_total 24461
telemt_me_reconnect_success_total 19817
telemt_me_reader_eof_total 21266
telemt_me_idle_close_by_peer_total 21263
telemt_me_route_drop_no_conn_total 369062
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 728178
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 691
telemt_desync_full_logged_total 225
telemt_desync_suppressed_total 466
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 20224
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 19810
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 407
telemt_user_connections_total{user="hello"} 701050
telemt_user_connections_current{user="hello"} 418
telemt_user_octets_from_client{user="hello"} 12245121528 (11.40 GB)
telemt_user_octets_to_client{user="hello"} 346971040024 (323.14 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 43
```