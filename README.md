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

# Server Metrics 2026-03-13 19:04:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 127877.1 (35h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 542588
telemt_connections_bad_total 12140
telemt_handshake_timeouts_total 12337
telemt_upstream_connect_attempt_total 32404
telemt_upstream_connect_success_total 32239
telemt_upstream_connect_fail_total 165
telemt_upstream_connect_attempts_per_request{bucket="1"} 32404
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14847
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17251
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 141
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 165
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 5038
telemt_me_reconnect_attempts_total 30104
telemt_me_reconnect_success_total 25456
telemt_me_reader_eof_total 27185
telemt_me_idle_close_by_peer_total 27184
telemt_me_route_drop_no_conn_total 178408
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 469154
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1496
telemt_desync_full_logged_total 516
telemt_desync_suppressed_total 980
telemt_desync_frames_bucket_total{bucket="1_2"} 327
telemt_desync_frames_bucket_total{bucket="3_10"} 549
telemt_desync_frames_bucket_total{bucket="gt_10"} 620
telemt_pool_swap_total 114
telemt_me_writer_removed_unexpected_total 25886
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 25440
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 430
telemt_user_connections_total{user="hello"} 469097
telemt_user_connections_current{user="hello"} 351
telemt_user_octets_from_client{user="hello"} 8671085398 (8.08 GB)
telemt_user_octets_to_client{user="hello"} 222723817752 (207.43 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 127770.0 (35h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 270675
telemt_connections_bad_total 1957
telemt_handshake_timeouts_total 1863
telemt_upstream_connect_attempt_total 122633
telemt_upstream_connect_success_total 121715
telemt_upstream_connect_fail_total 918
telemt_upstream_connect_attempts_per_request{bucket="1"} 122633
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 92160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27547
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2008
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 918
telemt_me_keepalive_timeout_total 3579
telemt_me_reconnect_attempts_total 132435
telemt_me_reconnect_success_total 26154
telemt_me_reader_eof_total 30217
telemt_me_idle_close_by_peer_total 30217
telemt_me_route_drop_no_conn_total 83164
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 167517
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
telemt_me_writer_removed_unexpected_total 29716
telemt_me_refill_failed_total 3316
telemt_me_writer_restored_same_endpoint_total 26137
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3562
telemt_user_connections_total{user="hello"} 256503
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 2641046798 (2.46 GB)
telemt_user_octets_to_client{user="hello"} 77515922667 (72.19 GB)
telemt_user_msgs_from_client{user="hello"} 1391843
telemt_user_msgs_to_client{user="hello"} 7856714
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 127734.2 (35h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 317798
telemt_connections_bad_total 2630
telemt_handshake_timeouts_total 20845
telemt_upstream_connect_attempt_total 33961
telemt_upstream_connect_success_total 33956
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 33961
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15718
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18199
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2749
telemt_me_reconnect_attempts_total 28784
telemt_me_reconnect_success_total 27549
telemt_me_reader_eof_total 29547
telemt_me_idle_close_by_peer_total 29547
telemt_me_route_drop_no_conn_total 113388
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 283209
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
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 27860
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 27529
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 311
telemt_user_connections_total{user="hello"} 283118
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 10398531040 (9.68 GB)
telemt_user_octets_to_client{user="hello"} 118535359660 (110.39 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 127709.2 (35h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 422602
telemt_connections_bad_total 15145
telemt_handshake_timeouts_total 3895
telemt_upstream_connect_attempt_total 61677
telemt_upstream_connect_success_total 51403
telemt_upstream_connect_fail_total 10274
telemt_upstream_connect_attempts_per_request{bucket="1"} 61677
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18740
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 294
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10274
telemt_me_keepalive_timeout_total 4706
telemt_me_reconnect_attempts_total 116628
telemt_me_reconnect_success_total 26007
telemt_me_reader_eof_total 29577
telemt_me_idle_close_by_peer_total 29570
telemt_me_route_drop_no_conn_total 146112
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 354256
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 27
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
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 29170
telemt_me_refill_failed_total 2826
telemt_me_writer_restored_same_endpoint_total 25997
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3163
telemt_user_connections_total{user="hello"} 373136
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 8467794807 (7.89 GB)
telemt_user_octets_to_client{user="hello"} 133198331592 (124.05 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 77880.7 (21h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130966
telemt_connections_bad_total 16056
telemt_handshake_timeouts_total 1414
telemt_upstream_connect_attempt_total 30115
telemt_upstream_connect_success_total 29832
telemt_upstream_connect_fail_total 283
telemt_upstream_connect_attempts_per_request{bucket="1"} 30115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15410
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14322
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 283
telemt_me_keepalive_timeout_total 1218
telemt_me_reconnect_attempts_total 34423
telemt_me_reconnect_success_total 21033
telemt_me_reader_eof_total 22545
telemt_me_idle_close_by_peer_total 22545
telemt_me_route_drop_no_conn_total 40976
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 104336
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 579
telemt_desync_full_logged_total 131
telemt_desync_suppressed_total 448
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 290
telemt_desync_frames_bucket_total{bucket="gt_10"} 208
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 21647
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 21015
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 614
telemt_user_connections_total{user="hello"} 109231
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 1260809829 (1.17 GB)
telemt_user_octets_to_client{user="hello"} 38345357667 (35.71 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 127665.6 (35h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 781996
telemt_connections_bad_total 24786
telemt_handshake_timeouts_total 24832
telemt_upstream_connect_attempt_total 26382
telemt_upstream_connect_success_total 26243
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 26382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12262
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13946
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 3033
telemt_me_reconnect_attempts_total 24564
telemt_me_reconnect_success_total 19919
telemt_me_reader_eof_total 21374
telemt_me_idle_close_by_peer_total 21371
telemt_me_route_drop_no_conn_total 371742
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 733328
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
telemt_pool_swap_total 118
telemt_me_writer_removed_unexpected_total 20328
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 19912
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 409
telemt_user_connections_total{user="hello"} 706196
telemt_user_connections_current{user="hello"} 460
telemt_user_octets_from_client{user="hello"} 12275724608 (11.43 GB)
telemt_user_octets_to_client{user="hello"} 348381307100 (324.46 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 56
```