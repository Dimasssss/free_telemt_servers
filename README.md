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

# Server Metrics 2026-03-13 18:34:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 126043.7 (35h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 532957
telemt_connections_bad_total 10457
telemt_handshake_timeouts_total 12190
telemt_upstream_connect_attempt_total 31624
telemt_upstream_connect_success_total 31469
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 31624
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17053
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3486
telemt_me_reconnect_attempts_total 29814
telemt_me_reconnect_success_total 25172
telemt_me_reader_eof_total 26883
telemt_me_idle_close_by_peer_total 26882
telemt_me_route_drop_no_conn_total 174277
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 462084
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
telemt_me_writer_removed_unexpected_total 25597
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 25156
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 425
telemt_user_connections_total{user="hello"} 461653
telemt_user_connections_current{user="hello"} 341
telemt_user_octets_from_client{user="hello"} 8479933376 (7.90 GB)
telemt_user_octets_to_client{user="hello"} 219321718224 (204.26 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 125936.3 (34h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 264288
telemt_connections_bad_total 1954
telemt_handshake_timeouts_total 1840
telemt_upstream_connect_attempt_total 116885
telemt_upstream_connect_success_total 116027
telemt_upstream_connect_fail_total 858
telemt_upstream_connect_attempts_per_request{bucket="1"} 116885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 87326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26937
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1764
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 858
telemt_me_keepalive_timeout_total 1532
telemt_me_reconnect_attempts_total 130080
telemt_me_reconnect_success_total 26033
telemt_me_reader_eof_total 30038
telemt_me_idle_close_by_peer_total 30038
telemt_me_route_drop_no_conn_total 83056
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
telemt_me_writer_removed_unexpected_total 29508
telemt_me_refill_failed_total 3247
telemt_me_writer_restored_same_endpoint_total 26016
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3475
telemt_user_connections_total{user="hello"} 250392
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 2612256227 (2.43 GB)
telemt_user_octets_to_client{user="hello"} 76679500948 (71.41 GB)
telemt_user_msgs_from_client{user="hello"} 1327189
telemt_user_msgs_to_client{user="hello"} 7593966
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 125900.4 (34h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 312472
telemt_connections_bad_total 2629
telemt_handshake_timeouts_total 19651
telemt_upstream_connect_attempt_total 33508
telemt_upstream_connect_success_total 33503
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 33508
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17945
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2705
telemt_me_reconnect_attempts_total 28418
telemt_me_reconnect_success_total 27185
telemt_me_reader_eof_total 29152
telemt_me_idle_close_by_peer_total 29152
telemt_me_route_drop_no_conn_total 111263
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 279220
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 106
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 35
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 115
telemt_me_writer_removed_unexpected_total 27489
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 27165
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 304
telemt_user_connections_total{user="hello"} 279128
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 10328903256 (9.62 GB)
telemt_user_octets_to_client{user="hello"} 115086014892 (107.18 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 125875.5 (34h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 417373
telemt_connections_bad_total 15139
telemt_handshake_timeouts_total 3888
telemt_upstream_connect_attempt_total 60931
telemt_upstream_connect_success_total 50671
telemt_upstream_connect_fail_total 10260
telemt_upstream_connect_attempts_per_request{bucket="1"} 60931
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32059
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18315
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 288
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10260
telemt_me_keepalive_timeout_total 4679
telemt_me_reconnect_attempts_total 115023
telemt_me_reconnect_success_total 25365
telemt_me_reader_eof_total 28900
telemt_me_idle_close_by_peer_total 28893
telemt_me_route_drop_no_conn_total 143930
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 349232
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1361
telemt_desync_full_logged_total 406
telemt_desync_suppressed_total 955
telemt_desync_frames_bucket_total{bucket="1_2"} 335
telemt_desync_frames_bucket_total{bucket="3_10"} 524
telemt_desync_frames_bucket_total{bucket="gt_10"} 502
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 28491
telemt_me_refill_failed_total 2796
telemt_me_writer_restored_same_endpoint_total 25355
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3126
telemt_user_connections_total{user="hello"} 368113
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 8406912503 (7.83 GB)
telemt_user_octets_to_client{user="hello"} 130870395304 (121.88 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 76047.1 (21h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126971
telemt_connections_bad_total 15732
telemt_handshake_timeouts_total 1407
telemt_upstream_connect_attempt_total 29685
telemt_upstream_connect_success_total 29407
telemt_upstream_connect_fail_total 278
telemt_upstream_connect_attempts_per_request{bucket="1"} 29685
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14120
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 278
telemt_me_keepalive_timeout_total 1202
telemt_me_reconnect_attempts_total 34085
telemt_me_reconnect_success_total 20695
telemt_me_reader_eof_total 22188
telemt_me_idle_close_by_peer_total 22188
telemt_me_route_drop_no_conn_total 39654
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 100817
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 493
telemt_desync_full_logged_total 109
telemt_desync_suppressed_total 384
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 261
telemt_desync_frames_bucket_total{bucket="gt_10"} 160
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 21304
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 20677
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 609
telemt_user_connections_total{user="hello"} 105714
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 1228516141 (1.14 GB)
telemt_user_octets_to_client{user="hello"} 35475104035 (33.04 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 125833.0 (34h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 770188
telemt_connections_bad_total 24770
telemt_handshake_timeouts_total 24635
telemt_upstream_connect_attempt_total 26082
telemt_upstream_connect_success_total 25944
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 26082
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12144
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13768
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_keepalive_timeout_total 3004
telemt_me_reconnect_attempts_total 24351
telemt_me_reconnect_success_total 19707
telemt_me_reader_eof_total 21147
telemt_me_idle_close_by_peer_total 21144
telemt_me_route_drop_no_conn_total 366295
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 722672
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
telemt_me_writer_removed_unexpected_total 20112
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 19700
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 405
telemt_user_connections_total{user="hello"} 695545
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 12182870316 (11.35 GB)
telemt_user_octets_to_client{user="hello"} 344193578804 (320.56 GB)
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 57
```