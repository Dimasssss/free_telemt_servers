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

# Server Metrics 2026-03-14 12:23:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 190196.5 (52h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 753283
telemt_connections_bad_total 35749
telemt_handshake_timeouts_total 14481
telemt_upstream_connect_attempt_total 48264
telemt_upstream_connect_success_total 48024
telemt_upstream_connect_fail_total 240
telemt_upstream_connect_attempts_per_request{bucket="1"} 48264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25873
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 240
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 6337
telemt_me_reconnect_attempts_total 43923
telemt_me_reconnect_success_total 38154
telemt_me_reader_eof_total 40795
telemt_me_idle_close_by_peer_total 40794
telemt_me_route_drop_no_conn_total 247620
telemt_me_route_drop_channel_closed_total 41
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 645874
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2751
telemt_desync_full_logged_total 919
telemt_desync_suppressed_total 1832
telemt_desync_frames_bucket_total{bucket="1_2"} 568
telemt_desync_frames_bucket_total{bucket="3_10"} 1032
telemt_desync_frames_bucket_total{bucket="gt_10"} 1151
telemt_pool_swap_total 173
telemt_me_writer_removed_unexpected_total 38743
telemt_me_refill_failed_total 173
telemt_me_writer_restored_same_endpoint_total 38134
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 589
telemt_user_connections_total{user="hello"} 645780
telemt_user_connections_current{user="hello"} 425
telemt_user_octets_from_client{user="hello"} 17904082518 (16.67 GB)
telemt_user_octets_to_client{user="hello"} 309751660180 (288.48 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 190089.5 (52h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 372900
telemt_connections_bad_total 2848
telemt_handshake_timeouts_total 3349
telemt_upstream_connect_attempt_total 158073
telemt_upstream_connect_success_total 156673
telemt_upstream_connect_fail_total 1400
telemt_upstream_connect_attempts_per_request{bucket="1"} 158073
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 113828
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40320
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2524
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1400
telemt_me_keepalive_timeout_total 5713
telemt_me_reconnect_attempts_total 196707
telemt_me_reconnect_success_total 42077
telemt_me_reader_eof_total 48000
telemt_me_idle_close_by_peer_total 48000
telemt_me_route_drop_no_conn_total 128699
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 246974
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 47
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
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 47309
telemt_me_refill_failed_total 4824
telemt_me_writer_restored_same_endpoint_total 42059
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5232
telemt_user_connections_total{user="hello"} 351867
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 3566551067 (3.32 GB)
telemt_user_octets_to_client{user="hello"} 113130963002 (105.36 GB)
telemt_user_msgs_from_client{user="hello"} 1713995
telemt_user_msgs_to_client{user="hello"} 9567945
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 190053.2 (52h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 429934
telemt_connections_bad_total 3321
telemt_handshake_timeouts_total 36674
telemt_upstream_connect_attempt_total 50777
telemt_upstream_connect_success_total 50768
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 50777
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23337
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27352
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4301
telemt_me_reconnect_attempts_total 42496
telemt_me_reconnect_success_total 41173
telemt_me_reader_eof_total 44231
telemt_me_idle_close_by_peer_total 44231
telemt_me_route_drop_no_conn_total 157553
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 374503
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 146
telemt_desync_full_logged_total 66
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 177
telemt_me_writer_removed_unexpected_total 41666
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 41152
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 493
telemt_user_connections_total{user="hello"} 374262
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 16204151234 (15.09 GB)
telemt_user_octets_to_client{user="hello"} 163742342279 (152.50 GB)
telemt_user_msgs_from_client{user="hello"} 166
telemt_user_msgs_to_client{user="hello"} 712
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 190028.6 (52h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 547162
telemt_connections_bad_total 16779
telemt_handshake_timeouts_total 5334
telemt_upstream_connect_attempt_total 81196
telemt_upstream_connect_success_total 70478
telemt_upstream_connect_fail_total 10718
telemt_upstream_connect_attempts_per_request{bucket="1"} 81196
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40938
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29139
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 392
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10718
telemt_me_keepalive_timeout_total 5855
telemt_me_reconnect_attempts_total 157811
telemt_me_reconnect_success_total 41952
telemt_me_reader_eof_total 46901
telemt_me_idle_close_by_peer_total 46893
telemt_me_route_drop_no_conn_total 197911
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 469289
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2175
telemt_desync_full_logged_total 636
telemt_desync_suppressed_total 1539
telemt_desync_frames_bucket_total{bucket="1_2"} 503
telemt_desync_frames_bucket_total{bucket="3_10"} 828
telemt_desync_frames_bucket_total{bucket="gt_10"} 844
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 46050
telemt_me_refill_failed_total 3612
telemt_me_writer_restored_same_endpoint_total 41942
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 4098
telemt_user_connections_total{user="hello"} 488152
telemt_user_connections_current{user="hello"} 226
telemt_user_octets_from_client{user="hello"} 10319790071 (9.61 GB)
telemt_user_octets_to_client{user="hello"} 201423181296 (187.59 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 140200.1 (38h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 238650
telemt_connections_bad_total 38461
telemt_handshake_timeouts_total 2195
telemt_upstream_connect_attempt_total 49354
telemt_upstream_connect_success_total 48856
telemt_upstream_connect_fail_total 498
telemt_upstream_connect_attempts_per_request{bucket="1"} 49354
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24337
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 498
telemt_me_keepalive_timeout_total 3133
telemt_me_reconnect_attempts_total 55156
telemt_me_reconnect_success_total 36994
telemt_me_reader_eof_total 39583
telemt_me_idle_close_by_peer_total 39583
telemt_me_route_drop_no_conn_total 72605
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 186711
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 812
telemt_desync_full_logged_total 197
telemt_desync_suppressed_total 615
telemt_desync_frames_bucket_total{bucket="1_2"} 134
telemt_desync_frames_bucket_total{bucket="3_10"} 382
telemt_desync_frames_bucket_total{bucket="gt_10"} 296
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 37909
telemt_me_refill_failed_total 563
telemt_me_writer_restored_same_endpoint_total 36976
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 915
telemt_user_connections_total{user="hello"} 191467
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 2772427873 (2.58 GB)
telemt_user_octets_to_client{user="hello"} 88023572071 (81.98 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 189985.0 (52h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1108921
telemt_connections_bad_total 37843
telemt_handshake_timeouts_total 27299
telemt_upstream_connect_attempt_total 39574
telemt_upstream_connect_success_total 39367
telemt_upstream_connect_fail_total 207
telemt_upstream_connect_attempts_per_request{bucket="1"} 39574
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18659
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20667
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 207
telemt_me_keepalive_timeout_total 5206
telemt_me_reconnect_attempts_total 34654
telemt_me_reconnect_success_total 29959
telemt_me_reader_eof_total 32122
telemt_me_idle_close_by_peer_total 32119
telemt_me_route_drop_no_conn_total 521758
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1028426
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 809
telemt_desync_full_logged_total 268
telemt_desync_suppressed_total 541
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 269
telemt_desync_frames_bucket_total{bucket="gt_10"} 280
telemt_pool_swap_total 177
telemt_me_writer_removed_unexpected_total 30486
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 29952
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 527
telemt_user_connections_total{user="hello"} 1001023
telemt_user_connections_current{user="hello"} 465
telemt_user_octets_from_client{user="hello"} 21445274116 (19.97 GB)
telemt_user_octets_to_client{user="hello"} 504110944796 (469.49 GB)
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 69
```