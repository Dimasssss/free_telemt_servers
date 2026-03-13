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

# Server Metrics 2026-03-13 23:44:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 144685.6 (40h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 585731
telemt_connections_bad_total 19588
telemt_handshake_timeouts_total 12838
telemt_upstream_connect_attempt_total 36816
telemt_upstream_connect_success_total 36633
telemt_upstream_connect_fail_total 183
telemt_upstream_connect_attempts_per_request{bucket="1"} 36816
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19744
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 183
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5161
telemt_me_reconnect_attempts_total 33697
telemt_me_reconnect_success_total 29030
telemt_me_reader_eof_total 31015
telemt_me_idle_close_by_peer_total 31014
telemt_me_route_drop_no_conn_total 192689
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 502557
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1624
telemt_desync_full_logged_total 554
telemt_desync_suppressed_total 1070
telemt_desync_frames_bucket_total{bucket="1_2"} 350
telemt_desync_frames_bucket_total{bucket="3_10"} 608
telemt_desync_frames_bucket_total{bucket="gt_10"} 666
telemt_pool_swap_total 130
telemt_me_writer_removed_unexpected_total 29498
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 29014
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 468
telemt_user_connections_total{user="hello"} 502452
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 15398725474 (14.34 GB)
telemt_user_octets_to_client{user="hello"} 249515642368 (232.38 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 144578.4 (40h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 299885
telemt_connections_bad_total 2180
telemt_handshake_timeouts_total 1928
telemt_upstream_connect_attempt_total 141323
telemt_upstream_connect_success_total 140263
telemt_upstream_connect_fail_total 1059
telemt_upstream_connect_attempts_per_request{bucket="1"} 141322
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106417
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31431
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1059
telemt_me_keepalive_timeout_total 3752
telemt_me_reconnect_attempts_total 152802
telemt_me_reconnect_success_total 29732
telemt_me_reader_eof_total 34359
telemt_me_idle_close_by_peer_total 34359
telemt_me_route_drop_no_conn_total 92174
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 181213
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 37
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
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 33854
telemt_me_refill_failed_total 3840
telemt_me_writer_restored_same_endpoint_total 29715
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4122
telemt_user_connections_total{user="hello"} 284325
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 2985091323 (2.78 GB)
telemt_user_octets_to_client{user="hello"} 89337638527 (83.20 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 144542.0 (40h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 350601
telemt_connections_bad_total 2741
telemt_handshake_timeouts_total 31638
telemt_upstream_connect_attempt_total 38365
telemt_upstream_connect_success_total 38359
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 38365
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20704
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2911
telemt_me_reconnect_attempts_total 32362
telemt_me_reconnect_success_total 31109
telemt_me_reader_eof_total 33405
telemt_me_idle_close_by_peer_total 33405
telemt_me_route_drop_no_conn_total 124136
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 303928
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
telemt_pool_swap_total 134
telemt_me_writer_removed_unexpected_total 31473
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 31089
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 364
telemt_user_connections_total{user="hello"} 303830
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 12535238404 (11.67 GB)
telemt_user_octets_to_client{user="hello"} 126096111968 (117.44 GB)
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 144517.6 (40h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 452166
telemt_connections_bad_total 15359
telemt_handshake_timeouts_total 4250
telemt_upstream_connect_attempt_total 66229
telemt_upstream_connect_success_total 55818
telemt_upstream_connect_fail_total 10411
telemt_upstream_connect_attempts_per_request{bucket="1"} 66229
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21062
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 315
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10411
telemt_me_keepalive_timeout_total 5029
telemt_me_reconnect_attempts_total 132053
telemt_me_reconnect_success_total 29573
telemt_me_reader_eof_total 33619
telemt_me_idle_close_by_peer_total 33611
telemt_me_route_drop_no_conn_total 158784
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 382396
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1672
telemt_desync_full_logged_total 491
telemt_desync_suppressed_total 1181
telemt_desync_frames_bucket_total{bucket="1_2"} 391
telemt_desync_frames_bucket_total{bucket="3_10"} 638
telemt_desync_frames_bucket_total{bucket="gt_10"} 643
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 33143
telemt_me_refill_failed_total 3196
telemt_me_writer_restored_same_endpoint_total 29563
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3570
telemt_user_connections_total{user="hello"} 401238
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 9023339655 (8.40 GB)
telemt_user_octets_to_client{user="hello"} 153221081560 (142.70 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 94689.3 (26h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 158774
telemt_connections_bad_total 23369
telemt_handshake_timeouts_total 1545
telemt_upstream_connect_attempt_total 35154
telemt_upstream_connect_success_total 34829
telemt_upstream_connect_fail_total 325
telemt_upstream_connect_attempts_per_request{bucket="1"} 35154
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17825
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16885
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 325
telemt_me_keepalive_timeout_total 1344
telemt_me_reconnect_attempts_total 38598
telemt_me_reconnect_success_total 25191
telemt_me_reader_eof_total 26943
telemt_me_idle_close_by_peer_total 26943
telemt_me_route_drop_no_conn_total 47987
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 124198
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 619
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 474
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 25840
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 25173
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 649
telemt_user_connections_total{user="hello"} 129052
telemt_user_connections_current{user="hello"} 51
telemt_user_octets_from_client{user="hello"} 1592742757 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 62130791047 (57.86 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 144473.7 (40h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 858783
telemt_connections_bad_total 27314
telemt_handshake_timeouts_total 25221
telemt_upstream_connect_attempt_total 29867
telemt_upstream_connect_success_total 29706
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 29867
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15810
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_timeout_total 3402
telemt_me_reconnect_attempts_total 27201
telemt_me_reconnect_success_total 22538
telemt_me_reader_eof_total 24156
telemt_me_idle_close_by_peer_total 24153
telemt_me_route_drop_no_conn_total 409413
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 801815
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 697
telemt_desync_full_logged_total 227
telemt_desync_suppressed_total 470
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 229
telemt_desync_frames_bucket_total{bucket="gt_10"} 219
telemt_pool_swap_total 134
telemt_me_writer_removed_unexpected_total 22977
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 22531
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 439
telemt_user_connections_total{user="hello"} 774667
telemt_user_connections_current{user="hello"} 232
telemt_user_octets_from_client{user="hello"} 13480966060 (12.56 GB)
telemt_user_octets_to_client{user="hello"} 395043879860 (367.91 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 31
```