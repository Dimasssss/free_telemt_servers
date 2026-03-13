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

# Server Metrics 2026-03-13 19:09:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 128182.9 (35h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 544208
telemt_connections_bad_total 12515
telemt_handshake_timeouts_total 12362
telemt_upstream_connect_attempt_total 32494
telemt_upstream_connect_success_total 32329
telemt_upstream_connect_fail_total 165
telemt_upstream_connect_attempts_per_request{bucket="1"} 32494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14894
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17294
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 141
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 165
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5041
telemt_me_reconnect_attempts_total 30177
telemt_me_reconnect_success_total 25528
telemt_me_reader_eof_total 27267
telemt_me_idle_close_by_peer_total 27266
telemt_me_route_drop_no_conn_total 179057
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 470353
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1507
telemt_desync_full_logged_total 518
telemt_desync_suppressed_total 989
telemt_desync_frames_bucket_total{bucket="1_2"} 329
telemt_desync_frames_bucket_total{bucket="3_10"} 552
telemt_desync_frames_bucket_total{bucket="gt_10"} 626
telemt_pool_swap_total 115
telemt_me_writer_removed_unexpected_total 25960
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 25512
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 432
telemt_user_connections_total{user="hello"} 470295
telemt_user_connections_current{user="hello"} 291
telemt_user_octets_from_client{user="hello"} 8680677938 (8.08 GB)
telemt_user_octets_to_client{user="hello"} 223328094400 (207.99 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 128075.8 (35h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 271526
telemt_connections_bad_total 1957
telemt_handshake_timeouts_total 1864
telemt_upstream_connect_attempt_total 123236
telemt_upstream_connect_success_total 122310
telemt_upstream_connect_fail_total 925
telemt_upstream_connect_attempts_per_request{bucket="1"} 123235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 92653
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27621
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2036
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 925
telemt_me_keepalive_timeout_total 3586
telemt_me_reconnect_attempts_total 133712
telemt_me_reconnect_success_total 26183
telemt_me_reader_eof_total 30286
telemt_me_idle_close_by_peer_total 30286
telemt_me_route_drop_no_conn_total 83203
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 167831
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 32
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
telemt_me_writer_removed_unexpected_total 29786
telemt_me_refill_failed_total 3355
telemt_me_writer_restored_same_endpoint_total 26166
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3603
telemt_user_connections_total{user="hello"} 257339
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 2644022651 (2.46 GB)
telemt_user_octets_to_client{user="hello"} 77639450741 (72.31 GB)
telemt_user_msgs_from_client{user="hello"} 1397205
telemt_user_msgs_to_client{user="hello"} 7887120
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 128040.1 (35h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 318517
telemt_connections_bad_total 2631
telemt_handshake_timeouts_total 21040
telemt_upstream_connect_attempt_total 34078
telemt_upstream_connect_success_total 34073
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 34078
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18258
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2760
telemt_me_reconnect_attempts_total 28858
telemt_me_reconnect_success_total 27623
telemt_me_reader_eof_total 29634
telemt_me_idle_close_by_peer_total 29634
telemt_me_route_drop_no_conn_total 113675
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 283724
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
telemt_pool_swap_total 118
telemt_me_writer_removed_unexpected_total 27934
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 27603
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 311
telemt_user_connections_total{user="hello"} 283633
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 10406329532 (9.69 GB)
telemt_user_octets_to_client{user="hello"} 119003881744 (110.83 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 128015.0 (35h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 423413
telemt_connections_bad_total 15163
telemt_handshake_timeouts_total 3908
telemt_upstream_connect_attempt_total 61804
telemt_upstream_connect_success_total 51530
telemt_upstream_connect_fail_total 10274
telemt_upstream_connect_attempts_per_request{bucket="1"} 61804
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32421
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18806
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 294
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10274
telemt_me_keepalive_timeout_total 4712
telemt_me_reconnect_attempts_total 116712
telemt_me_reconnect_success_total 26091
telemt_me_reader_eof_total 29686
telemt_me_idle_close_by_peer_total 29679
telemt_me_route_drop_no_conn_total 146375
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 355019
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1388
telemt_desync_full_logged_total 418
telemt_desync_suppressed_total 970
telemt_desync_frames_bucket_total{bucket="1_2"} 346
telemt_desync_frames_bucket_total{bucket="3_10"} 529
telemt_desync_frames_bucket_total{bucket="gt_10"} 513
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 29256
telemt_me_refill_failed_total 2826
telemt_me_writer_restored_same_endpoint_total 26081
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3165
telemt_user_connections_total{user="hello"} 373899
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 8474614359 (7.89 GB)
telemt_user_octets_to_client{user="hello"} 133607923496 (124.43 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 78186.5 (21h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131784
telemt_connections_bad_total 16110
telemt_handshake_timeouts_total 1414
telemt_upstream_connect_attempt_total 30171
telemt_upstream_connect_success_total 29888
telemt_upstream_connect_fail_total 283
telemt_upstream_connect_attempts_per_request{bucket="1"} 30171
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15436
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14352
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 283
telemt_me_keepalive_timeout_total 1226
telemt_me_reconnect_attempts_total 34479
telemt_me_reconnect_success_total 21089
telemt_me_reader_eof_total 22601
telemt_me_idle_close_by_peer_total 22601
telemt_me_route_drop_no_conn_total 41173
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 105039
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 585
telemt_desync_full_logged_total 133
telemt_desync_suppressed_total 452
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 293
telemt_desync_frames_bucket_total{bucket="gt_10"} 211
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 21703
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 21071
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 614
telemt_user_connections_total{user="hello"} 109934
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 1266476509 (1.18 GB)
telemt_user_octets_to_client{user="hello"} 38607821931 (35.96 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 127971.3 (35h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 784239
telemt_connections_bad_total 24786
telemt_handshake_timeouts_total 24838
telemt_upstream_connect_attempt_total 26463
telemt_upstream_connect_success_total 26322
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 26462
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13980
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_keepalive_timeout_total 3040
telemt_me_reconnect_attempts_total 24601
telemt_me_reconnect_success_total 19955
telemt_me_reader_eof_total 21415
telemt_me_idle_close_by_peer_total 21412
telemt_me_route_drop_no_conn_total 372895
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 735167
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
telemt_pool_swap_total 119
telemt_me_writer_removed_unexpected_total 20366
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 19948
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 411
telemt_user_connections_total{user="hello"} 708035
telemt_user_connections_current{user="hello"} 495
telemt_user_octets_from_client{user="hello"} 12290188572 (11.45 GB)
telemt_user_octets_to_client{user="hello"} 349426577000 (325.43 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 69
```