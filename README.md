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

# Server Metrics 2026-03-14 04:14:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 160879.8 (44h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 624864
telemt_connections_bad_total 31220
telemt_handshake_timeouts_total 12942
telemt_upstream_connect_attempt_total 41130
telemt_upstream_connect_success_total 40921
telemt_upstream_connect_fail_total 208
telemt_upstream_connect_attempts_per_request{bucket="1"} 41129
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18684
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22086
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 208
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5548
telemt_me_reconnect_attempts_total 37206
telemt_me_reconnect_success_total 32522
telemt_me_reader_eof_total 34756
telemt_me_idle_close_by_peer_total 34755
telemt_me_route_drop_no_conn_total 202930
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 529070
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1816
telemt_desync_full_logged_total 612
telemt_desync_suppressed_total 1204
telemt_desync_frames_bucket_total{bucket="1_2"} 386
telemt_desync_frames_bucket_total{bucket="3_10"} 670
telemt_desync_frames_bucket_total{bucket="gt_10"} 760
telemt_pool_swap_total 147
telemt_me_writer_removed_unexpected_total 33024
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 32502
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 502
telemt_user_connections_total{user="hello"} 528959
telemt_user_connections_current{user="hello"} 264
telemt_user_octets_from_client{user="hello"} 15737610906 (14.66 GB)
telemt_user_octets_to_client{user="hello"} 257580613864 (239.89 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 160772.8 (44h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 315875
telemt_connections_bad_total 2267
telemt_handshake_timeouts_total 2264
telemt_upstream_connect_attempt_total 146817
telemt_upstream_connect_success_total 145636
telemt_upstream_connect_fail_total 1181
telemt_upstream_connect_attempts_per_request{bucket="1"} 146817
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 108580
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34639
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2417
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1181
telemt_me_keepalive_timeout_total 3866
telemt_me_reconnect_attempts_total 169876
telemt_me_reconnect_success_total 34316
telemt_me_reader_eof_total 39450
telemt_me_idle_close_by_peer_total 39450
telemt_me_route_drop_no_conn_total 99912
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 196118
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 38881
telemt_me_refill_failed_total 4230
telemt_me_writer_restored_same_endpoint_total 34299
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4565
telemt_user_connections_total{user="hello"} 299230
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 3121280491 (2.91 GB)
telemt_user_octets_to_client{user="hello"} 96808880783 (90.16 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 160736.4 (44h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 368478
telemt_connections_bad_total 2922
telemt_handshake_timeouts_total 34794
telemt_upstream_connect_attempt_total 42625
telemt_upstream_connect_success_total 42616
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 42625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19475
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23074
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3390
telemt_me_reconnect_attempts_total 35842
telemt_me_reconnect_success_total 34562
telemt_me_reader_eof_total 37148
telemt_me_idle_close_by_peer_total 37148
telemt_me_route_drop_no_conn_total 131746
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 317988
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
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
telemt_pool_swap_total 151
telemt_me_writer_removed_unexpected_total 34983
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 34541
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 421
telemt_user_connections_total{user="hello"} 317787
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 12679403060 (11.81 GB)
telemt_user_octets_to_client{user="hello"} 128039915792 (119.25 GB)
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 160711.9 (44h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 470226
telemt_connections_bad_total 15548
telemt_handshake_timeouts_total 4406
telemt_upstream_connect_attempt_total 72337
telemt_upstream_connect_success_total 61829
telemt_upstream_connect_fail_total 10508
telemt_upstream_connect_attempts_per_request{bucket="1"} 72337
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36896
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24593
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 331
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10508
telemt_me_keepalive_timeout_total 5278
telemt_me_reconnect_attempts_total 140833
telemt_me_reconnect_success_total 34787
telemt_me_reader_eof_total 39176
telemt_me_idle_close_by_peer_total 39168
telemt_me_route_drop_no_conn_total 167979
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 399013
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1710
telemt_desync_full_logged_total 503
telemt_desync_suppressed_total 1207
telemt_desync_frames_bucket_total{bucket="1_2"} 401
telemt_desync_frames_bucket_total{bucket="3_10"} 647
telemt_desync_frames_bucket_total{bucket="gt_10"} 662
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 38500
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 34777
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3713
telemt_user_connections_total{user="hello"} 417862
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 9187527611 (8.56 GB)
telemt_user_octets_to_client{user="hello"} 162952371028 (151.76 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 110883.4 (30h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183074
telemt_connections_bad_total 26425
telemt_handshake_timeouts_total 1640
telemt_upstream_connect_attempt_total 40037
telemt_upstream_connect_success_total 39666
telemt_upstream_connect_fail_total 371
telemt_upstream_connect_attempts_per_request{bucket="1"} 40037
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19982
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19553
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 131
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 371
telemt_me_keepalive_timeout_total 2376
telemt_me_reconnect_attempts_total 42658
telemt_me_reconnect_success_total 29238
telemt_me_reader_eof_total 31292
telemt_me_idle_close_by_peer_total 31292
telemt_me_route_drop_no_conn_total 54120
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 145082
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 622
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 29922
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 29220
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 684
telemt_user_connections_total{user="hello"} 149837
telemt_user_connections_current{user="hello"} 50
telemt_user_octets_from_client{user="hello"} 2229868525 (2.08 GB)
telemt_user_octets_to_client{user="hello"} 68807093271 (64.08 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 160667.9 (44h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 914935
telemt_connections_bad_total 28167
telemt_handshake_timeouts_total 25484
telemt_upstream_connect_attempt_total 33428
telemt_upstream_connect_success_total 33249
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 33428
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17634
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_timeout_total 4576
telemt_me_reconnect_attempts_total 29966
telemt_me_reconnect_success_total 25296
telemt_me_reader_eof_total 27149
telemt_me_idle_close_by_peer_total 27146
telemt_me_route_drop_no_conn_total 435460
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 854218
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 760
telemt_desync_full_logged_total 250
telemt_desync_suppressed_total 510
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 151
telemt_me_writer_removed_unexpected_total 25763
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 25289
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 467
telemt_user_connections_total{user="hello"} 826883
telemt_user_connections_current{user="hello"} 283
telemt_user_octets_from_client{user="hello"} 14414557112 (13.42 GB)
telemt_user_octets_to_client{user="hello"} 416322736488 (387.73 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 38
```