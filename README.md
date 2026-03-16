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

# Server Metrics 2026-03-16 01:21:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 97593.8 (27h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 423050
telemt_connections_bad_total 5358
telemt_handshake_timeouts_total 14298
telemt_upstream_connect_attempt_total 23347
telemt_upstream_connect_success_total 23237
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 23347
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12892
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 21806
telemt_me_reconnect_success_total 18392
telemt_me_reader_eof_total 19659
telemt_me_idle_close_by_peer_total 19659
telemt_me_route_drop_no_conn_total 493665
telemt_me_route_drop_channel_closed_total 79
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 448505
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2216
telemt_desync_full_logged_total 892
telemt_desync_suppressed_total 1324
telemt_desync_frames_bucket_total{bucket="1_2"} 433
telemt_desync_frames_bucket_total{bucket="3_10"} 862
telemt_desync_frames_bucket_total{bucket="gt_10"} 921
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 18701
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 18358
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 309
telemt_user_connections_total{user="hello"} 387577
telemt_user_connections_current{user="hello"} 252
telemt_user_octets_from_client{user="hello"} 8273216200 (7.71 GB)
telemt_user_octets_to_client{user="hello"} 283086434136 (263.64 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 97600.1 (27h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175240
telemt_connections_bad_total 2958
telemt_handshake_timeouts_total 14550
telemt_upstream_connect_attempt_total 26628
telemt_upstream_connect_success_total 26553
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 26628
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14385
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 609
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1305
telemt_me_reconnect_attempts_total 28189
telemt_me_reconnect_success_total 21287
telemt_me_reader_eof_total 22790
telemt_me_idle_close_by_peer_total 22789
telemt_me_route_drop_no_conn_total 71018
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 150662
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
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
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 21808
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 21271
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 521
telemt_user_connections_total{user="hello"} 150923
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 3398672073 (3.17 GB)
telemt_user_octets_to_client{user="hello"} 78028123276 (72.67 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 97592.7 (27h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 187656
telemt_connections_bad_total 2165
telemt_handshake_timeouts_total 3658
telemt_upstream_connect_attempt_total 27736
telemt_upstream_connect_success_total 27728
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 27736
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12022
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15653
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 30201
telemt_me_reconnect_success_total 22819
telemt_me_reader_eof_total 24554
telemt_me_idle_close_by_peer_total 24553
telemt_me_route_drop_no_conn_total 68312
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 154547
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
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 23271
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 22811
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 452
telemt_user_connections_total{user="hello"} 154422
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 14273506804 (13.29 GB)
telemt_user_octets_to_client{user="hello"} 99321743756 (92.50 GB)
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 97592.4 (27h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 256460
telemt_connections_bad_total 1215
telemt_handshake_timeouts_total 1648
telemt_upstream_connect_attempt_total 22862
telemt_upstream_connect_success_total 22841
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 22862
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10949
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11778
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 18100
telemt_me_reconnect_success_total 17990
telemt_me_reader_eof_total 19191
telemt_me_idle_close_by_peer_total 19191
telemt_me_route_drop_no_conn_total 92540
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 236946
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 879
telemt_desync_full_logged_total 310
telemt_desync_suppressed_total 569
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 380
telemt_desync_frames_bucket_total{bucket="gt_10"} 324
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 18209
telemt_me_writer_restored_same_endpoint_total 17979
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 219
telemt_user_connections_total{user="hello"} 236858
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 4128806308 (3.85 GB)
telemt_user_octets_to_client{user="hello"} 107897440264 (100.49 GB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 72663.9 (20h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 165360
telemt_connections_bad_total 29793
telemt_handshake_timeouts_total 2830
telemt_upstream_connect_attempt_total 20804
telemt_upstream_connect_success_total 20684
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 20804
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9243
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11319
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 122
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 111370
telemt_me_reconnect_success_total 16908
telemt_me_reader_eof_total 17918
telemt_me_idle_close_by_peer_total 17918
telemt_me_route_drop_no_conn_total 52153
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 128148
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 339
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 259
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 17036
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 16804
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 128
telemt_user_connections_total{user="hello"} 128268
telemt_user_connections_current{user="hello"} 50
telemt_user_octets_from_client{user="hello"} 1865110977 (1.74 GB)
telemt_user_octets_to_client{user="hello"} 44639985759 (41.57 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 97591.5 (27h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 639965
telemt_connections_bad_total 58665
telemt_handshake_timeouts_total 4889
telemt_upstream_connect_attempt_total 20686
telemt_upstream_connect_success_total 20570
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 20686
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9796
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10732
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 17017
telemt_me_reconnect_success_total 15696
telemt_me_reader_eof_total 16736
telemt_me_idle_close_by_peer_total 16736
telemt_me_route_drop_no_conn_total 580327
telemt_me_route_drop_channel_closed_total 96
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 676609
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 336
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 240
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 15919
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 15669
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 223
telemt_user_connections_total{user="hello"} 535287
telemt_user_connections_current{user="hello"} 249
telemt_user_octets_from_client{user="hello"} 12727972756 (11.85 GB)
telemt_user_octets_to_client{user="hello"} 330699585432 (307.99 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 21
```