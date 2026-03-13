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

# Server Metrics 2026-03-13 19:45:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 130323.5 (36h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 552313
telemt_connections_bad_total 13726
telemt_handshake_timeouts_total 12478
telemt_upstream_connect_attempt_total 33004
telemt_upstream_connect_success_total 32837
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 33004
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17583
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5048
telemt_me_reconnect_attempts_total 30596
telemt_me_reconnect_success_total 25945
telemt_me_reader_eof_total 27697
telemt_me_idle_close_by_peer_total 27696
telemt_me_route_drop_no_conn_total 182589
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 476651
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1535
telemt_desync_full_logged_total 523
telemt_desync_suppressed_total 1012
telemt_desync_frames_bucket_total{bucket="1_2"} 333
telemt_desync_frames_bucket_total{bucket="3_10"} 564
telemt_desync_frames_bucket_total{bucket="gt_10"} 638
telemt_pool_swap_total 116
telemt_me_writer_removed_unexpected_total 26381
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 25929
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 436
telemt_user_connections_total{user="hello"} 476546
telemt_user_connections_current{user="hello"} 297
telemt_user_octets_from_client{user="hello"} 8792931510 (8.19 GB)
telemt_user_octets_to_client{user="hello"} 227706654348 (212.07 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 130216.3 (36h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 276702
telemt_connections_bad_total 2098
telemt_handshake_timeouts_total 1875
telemt_upstream_connect_attempt_total 127715
telemt_upstream_connect_success_total 126773
telemt_upstream_connect_fail_total 942
telemt_upstream_connect_attempts_per_request{bucket="1"} 127715
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 96352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28184
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2237
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 942
telemt_me_keepalive_timeout_total 3614
telemt_me_reconnect_attempts_total 136547
telemt_me_reconnect_success_total 26326
telemt_me_reader_eof_total 30508
telemt_me_idle_close_by_peer_total 30508
telemt_me_route_drop_no_conn_total 83714
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168492
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 33
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
telemt_me_writer_removed_unexpected_total 30016
telemt_me_refill_failed_total 3439
telemt_me_writer_restored_same_endpoint_total 26309
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3690
telemt_user_connections_total{user="hello"} 262233
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 2703147768 (2.52 GB)
telemt_user_octets_to_client{user="hello"} 78916944219 (73.50 GB)
telemt_user_msgs_from_client{user="hello"} 1477654
telemt_user_msgs_to_client{user="hello"} 8232010
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 130179.9 (36h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 323830
telemt_connections_bad_total 2635
telemt_handshake_timeouts_total 22373
telemt_upstream_connect_attempt_total 34552
telemt_upstream_connect_success_total 34547
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 34552
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15987
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18520
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2788
telemt_me_reconnect_attempts_total 29246
telemt_me_reconnect_success_total 28008
telemt_me_reader_eof_total 30049
telemt_me_idle_close_by_peer_total 30049
telemt_me_route_drop_no_conn_total 115843
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 287555
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
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 28326
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 27988
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 318
telemt_user_connections_total{user="hello"} 287465
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 11764567468 (10.96 GB)
telemt_user_octets_to_client{user="hello"} 120371063672 (112.10 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 130155.5 (36h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 428653
telemt_connections_bad_total 15207
telemt_handshake_timeouts_total 4145
telemt_upstream_connect_attempt_total 62531
telemt_upstream_connect_success_total 52238
telemt_upstream_connect_fail_total 10293
telemt_upstream_connect_attempts_per_request{bucket="1"} 62531
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32734
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19199
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 296
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10293
telemt_me_keepalive_timeout_total 4725
telemt_me_reconnect_attempts_total 117334
telemt_me_reconnect_success_total 26712
telemt_me_reader_eof_total 30311
telemt_me_idle_close_by_peer_total 30304
telemt_me_route_drop_no_conn_total 148406
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 359902
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1454
telemt_desync_full_logged_total 434
telemt_desync_suppressed_total 1020
telemt_desync_frames_bucket_total{bucket="1_2"} 349
telemt_desync_frames_bucket_total{bucket="3_10"} 554
telemt_desync_frames_bucket_total{bucket="gt_10"} 551
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 29881
telemt_me_refill_failed_total 2826
telemt_me_writer_restored_same_endpoint_total 26702
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3169
telemt_user_connections_total{user="hello"} 378767
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 8574889223 (7.99 GB)
telemt_user_octets_to_client{user="hello"} 136640359908 (127.26 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 80326.9 (22h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136181
telemt_connections_bad_total 17085
telemt_handshake_timeouts_total 1426
telemt_upstream_connect_attempt_total 30795
telemt_upstream_connect_success_total 30501
telemt_upstream_connect_fail_total 294
telemt_upstream_connect_attempts_per_request{bucket="1"} 30795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15745
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14654
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 294
telemt_me_keepalive_timeout_total 1250
telemt_me_reconnect_attempts_total 34963
telemt_me_reconnect_success_total 21572
telemt_me_reader_eof_total 23120
telemt_me_idle_close_by_peer_total 23120
telemt_me_route_drop_no_conn_total 42645
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 108359
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 598
telemt_desync_full_logged_total 138
telemt_desync_suppressed_total 460
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 299
telemt_desync_frames_bucket_total{bucket="gt_10"} 214
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 22189
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 21554
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 617
telemt_user_connections_total{user="hello"} 113253
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 1317885313 (1.23 GB)
telemt_user_octets_to_client{user="hello"} 46577019343 (43.38 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 130111.9 (36h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 797150
telemt_connections_bad_total 24805
telemt_handshake_timeouts_total 24892
telemt_upstream_connect_attempt_total 26814
telemt_upstream_connect_success_total 26672
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 26814
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14171
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_timeout_total 3052
telemt_me_reconnect_attempts_total 24863
telemt_me_reconnect_success_total 20216
telemt_me_reader_eof_total 21693
telemt_me_idle_close_by_peer_total 21690
telemt_me_route_drop_no_conn_total 379506
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 747412
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
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 20632
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 20209
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 416
telemt_user_connections_total{user="hello"} 720277
telemt_user_connections_current{user="hello"} 406
telemt_user_octets_from_client{user="hello"} 12467180344 (11.61 GB)
telemt_user_octets_to_client{user="hello"} 353661734856 (329.37 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 43
```