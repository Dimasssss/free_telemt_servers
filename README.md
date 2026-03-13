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

# Server Metrics 2026-03-13 20:00:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 131239.6 (36h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 555346
telemt_connections_bad_total 14244
telemt_handshake_timeouts_total 12548
telemt_upstream_connect_attempt_total 33229
telemt_upstream_connect_success_total 33061
telemt_upstream_connect_fail_total 168
telemt_upstream_connect_attempts_per_request{bucket="1"} 33229
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15210
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17709
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 168
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5048
telemt_me_reconnect_attempts_total 30776
telemt_me_reconnect_success_total 26125
telemt_me_reader_eof_total 27894
telemt_me_idle_close_by_peer_total 27893
telemt_me_route_drop_no_conn_total 183700
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 479040
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
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 26565
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 26109
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 440
telemt_user_connections_total{user="hello"} 478935
telemt_user_connections_current{user="hello"} 262
telemt_user_octets_from_client{user="hello"} 8845782438 (8.24 GB)
telemt_user_octets_to_client{user="hello"} 228977679704 (213.25 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 131132.3 (36h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 279360
telemt_connections_bad_total 2098
telemt_handshake_timeouts_total 1876
telemt_upstream_connect_attempt_total 130196
telemt_upstream_connect_success_total 129244
telemt_upstream_connect_fail_total 952
telemt_upstream_connect_attempts_per_request{bucket="1"} 130196
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 98540
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28385
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2319
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 952
telemt_me_keepalive_timeout_total 3616
telemt_me_reconnect_attempts_total 137967
telemt_me_reconnect_success_total 26369
telemt_me_reader_eof_total 30593
telemt_me_idle_close_by_peer_total 30593
telemt_me_route_drop_no_conn_total 83775
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168733
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
telemt_me_writer_removed_unexpected_total 30101
telemt_me_refill_failed_total 3482
telemt_me_writer_restored_same_endpoint_total 26352
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3732
telemt_user_connections_total{user="hello"} 264858
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 2726170358 (2.54 GB)
telemt_user_octets_to_client{user="hello"} 79640421989 (74.17 GB)
telemt_user_msgs_from_client{user="hello"} 1541798
telemt_user_msgs_to_client{user="hello"} 8458923
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 131096.2 (36h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 325852
telemt_connections_bad_total 2636
telemt_handshake_timeouts_total 22969
telemt_upstream_connect_attempt_total 34765
telemt_upstream_connect_success_total 34760
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 34765
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16080
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18639
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2801
telemt_me_reconnect_attempts_total 29416
telemt_me_reconnect_success_total 28178
telemt_me_reader_eof_total 30230
telemt_me_idle_close_by_peer_total 30230
telemt_me_route_drop_no_conn_total 116429
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 288884
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
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 28496
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 28158
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 318
telemt_user_connections_total{user="hello"} 288795
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 11808415028 (11.00 GB)
telemt_user_octets_to_client{user="hello"} 120572741752 (112.29 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 131071.6 (36h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 430779
telemt_connections_bad_total 15228
telemt_handshake_timeouts_total 4158
telemt_upstream_connect_attempt_total 62877
telemt_upstream_connect_success_total 52580
telemt_upstream_connect_fail_total 10297
telemt_upstream_connect_attempts_per_request{bucket="1"} 62877
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19400
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 297
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10297
telemt_me_keepalive_timeout_total 4754
telemt_me_reconnect_attempts_total 118849
telemt_me_reconnect_success_total 27010
telemt_me_reader_eof_total 30650
telemt_me_idle_close_by_peer_total 30643
telemt_me_route_drop_no_conn_total 149423
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 361918
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1469
telemt_desync_full_logged_total 438
telemt_desync_suppressed_total 1031
telemt_desync_frames_bucket_total{bucket="1_2"} 354
telemt_desync_frames_bucket_total{bucket="3_10"} 557
telemt_desync_frames_bucket_total{bucket="gt_10"} 558
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 30221
telemt_me_refill_failed_total 2864
telemt_me_writer_restored_same_endpoint_total 27000
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3211
telemt_user_connections_total{user="hello"} 380783
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 8622392275 (8.03 GB)
telemt_user_octets_to_client{user="hello"} 138028806568 (128.55 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 81243.2 (22h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138371
telemt_connections_bad_total 17662
telemt_handshake_timeouts_total 1427
telemt_upstream_connect_attempt_total 31043
telemt_upstream_connect_success_total 30745
telemt_upstream_connect_fail_total 298
telemt_upstream_connect_attempts_per_request{bucket="1"} 31043
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15864
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14778
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 298
telemt_me_keepalive_timeout_total 1254
telemt_me_reconnect_attempts_total 35164
telemt_me_reconnect_success_total 21773
telemt_me_reader_eof_total 23322
telemt_me_idle_close_by_peer_total 23322
telemt_me_route_drop_no_conn_total 43167
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109936
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 604
telemt_desync_full_logged_total 140
telemt_desync_suppressed_total 464
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 302
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 22391
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 21755
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 618
telemt_user_connections_total{user="hello"} 114830
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 1336014369 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 50402752579 (46.94 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 131027.8 (36h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 802919
telemt_connections_bad_total 24815
telemt_handshake_timeouts_total 24907
telemt_upstream_connect_attempt_total 27036
telemt_upstream_connect_success_total 26893
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 27036
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12565
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14292
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 3088
telemt_me_reconnect_attempts_total 25039
telemt_me_reconnect_success_total 20392
telemt_me_reader_eof_total 21872
telemt_me_idle_close_by_peer_total 21869
telemt_me_route_drop_no_conn_total 382039
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 752960
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
telemt_me_writer_removed_unexpected_total 20811
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 20385
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 419
telemt_user_connections_total{user="hello"} 725819
telemt_user_connections_current{user="hello"} 518
telemt_user_octets_from_client{user="hello"} 12581664044 (11.72 GB)
telemt_user_octets_to_client{user="hello"} 356171347676 (331.71 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 78
```