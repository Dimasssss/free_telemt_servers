# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-19 14:55:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 43.7 (0h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2193
telemt_connections_current 125
telemt_connections_direct_current 125
telemt_handshake_timeouts_total 504
telemt_upstream_connect_attempt_total 213
telemt_upstream_connect_success_total 213
telemt_upstream_connect_attempts_per_request{bucket="1"} 213
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 211
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 751725 (734.11 KB)
telemt_user_octets_to_client{user="hello"} 82359058 (78.54 MB)
telemt_user_msgs_from_client{user="hello"} 1974
telemt_user_msgs_to_client{user="hello"} 5058
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 7938.9 (2h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 847462
telemt_connections_bad_total 29121
telemt_connections_current 4012
telemt_connections_me_current 4012
telemt_handshake_timeouts_total 17618
telemt_upstream_connect_attempt_total 2816
telemt_upstream_connect_success_total 2793
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 2816
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2067
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 703
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 5345
telemt_me_reconnect_success_total 1130
telemt_me_reader_eof_total 1234
telemt_me_idle_close_by_peer_total 1234
telemt_me_route_drop_no_conn_total 643619
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 725927
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2664
telemt_desync_full_logged_total 861
telemt_desync_suppressed_total 1803
telemt_desync_frames_bucket_total{bucket="1_2"} 475
telemt_desync_frames_bucket_total{bucket="3_10"} 1043
telemt_desync_frames_bucket_total{bucket="gt_10"} 1146
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 26
telemt_me_writer_removed_unexpected_total 1250
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 1075
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 120
telemt_user_connections_total{user="hello"} 726232
telemt_user_connections_current{user="hello"} 4012
telemt_user_octets_from_client{user="hello"} 9100461846 (8.48 GB)
telemt_user_octets_to_client{user="hello"} 196450901454 (182.96 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1362
telemt_user_unique_ips_recent_window{user="hello"} 612
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 7917.0 (2h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 832508
telemt_connections_bad_total 94436
telemt_connections_current 3098
telemt_connections_me_current 3098
telemt_handshake_timeouts_total 8184
telemt_upstream_connect_attempt_total 1323
telemt_upstream_connect_success_total 1311
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 737
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 570
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1784
telemt_me_reconnect_success_total 879
telemt_me_reader_eof_total 833
telemt_me_idle_close_by_peer_total 832
telemt_me_route_drop_no_conn_total 765670
telemt_me_route_drop_channel_closed_total 73
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 632967
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2229
telemt_desync_full_logged_total 588
telemt_desync_suppressed_total 1641
telemt_desync_frames_bucket_total{bucket="1_2"} 644
telemt_desync_frames_bucket_total{bucket="3_10"} 813
telemt_desync_frames_bucket_total{bucket="gt_10"} 772
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 31
telemt_me_writer_removed_unexpected_total 846
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 878
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 630210
telemt_user_connections_current{user="hello"} 3098
telemt_user_octets_from_client{user="hello"} 6568317828 (6.12 GB)
telemt_user_octets_to_client{user="hello"} 167047856080 (155.58 GB)
telemt_user_unique_ips_current{user="hello"} 1084
telemt_user_unique_ips_recent_window{user="hello"} 480
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 7905.1 (2h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 666409
telemt_connections_bad_total 43142
telemt_connections_current 2956
telemt_connections_me_current 2956
telemt_handshake_timeouts_total 10580
telemt_upstream_connect_attempt_total 10383
telemt_upstream_connect_success_total 9886
telemt_upstream_connect_fail_total 497
telemt_upstream_connect_attempts_per_request{bucket="1"} 10383
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8014
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1697
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 156
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 497
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 1300
telemt_me_reconnect_success_total 994
telemt_me_reader_eof_total 970
telemt_me_idle_close_by_peer_total 969
telemt_me_route_drop_no_conn_total 443435
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 553217
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2431
telemt_desync_full_logged_total 797
telemt_desync_suppressed_total 1634
telemt_desync_frames_bucket_total{bucket="1_2"} 500
telemt_desync_frames_bucket_total{bucket="3_10"} 948
telemt_desync_frames_bucket_total{bucket="gt_10"} 983
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 76
telemt_me_writer_removed_unexpected_total 1109
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 990
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 561195
telemt_user_connections_current{user="hello"} 2956
telemt_user_octets_from_client{user="hello"} 10666789243 (9.93 GB)
telemt_user_octets_to_client{user="hello"} 127485110612 (118.73 GB)
telemt_user_msgs_from_client{user="hello"} 16739
telemt_user_msgs_to_client{user="hello"} 18599
telemt_user_unique_ips_current{user="hello"} 1015
telemt_user_unique_ips_recent_window{user="hello"} 481
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 61628.2 (17h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4315813
telemt_connections_bad_total 808985
telemt_connections_current 3642
telemt_connections_me_current 3642
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 83249
telemt_upstream_connect_attempt_total 62866
telemt_upstream_connect_success_total 60382
telemt_upstream_connect_fail_total 2484
telemt_upstream_connect_attempts_per_request{bucket="1"} 62866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51899
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7461
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1022
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2484
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 73499
telemt_me_reconnect_success_total 8101
telemt_me_reader_eof_total 8528
telemt_me_idle_close_by_peer_total 8525
telemt_me_route_drop_no_conn_total 2037119
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2959247
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12769
telemt_desync_full_logged_total 3942
telemt_desync_suppressed_total 8827
telemt_desync_frames_bucket_total{bucket="1_2"} 2172
telemt_desync_frames_bucket_total{bucket="3_10"} 5474
telemt_desync_frames_bucket_total{bucket="gt_10"} 5123
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 8314
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 8077
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 213
telemt_user_connections_total{user="hello"} 3007877
telemt_user_connections_current{user="hello"} 3642
telemt_user_octets_from_client{user="hello"} 47900793419 (44.61 GB)
telemt_user_octets_to_client{user="hello"} 1066906449980 (993.63 GB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1164
telemt_user_unique_ips_recent_window{user="hello"} 599
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 7869.4 (2h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179281
telemt_connections_bad_total 9158
telemt_connections_current 1039
telemt_connections_me_current 1039
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 6125
telemt_upstream_connect_attempt_total 4175
telemt_upstream_connect_success_total 4038
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 4175
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2404
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_reconnect_attempts_total 1099
telemt_me_reconnect_success_total 1071
telemt_me_reader_eof_total 1053
telemt_me_idle_close_by_peer_total 1053
telemt_me_route_drop_no_conn_total 117381
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 152627
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 464
telemt_me_writer_pick_total{mode="p2c",result="full"} 2833
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_writer_pick_blocking_fallback_total 3285
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 426
telemt_desync_full_logged_total 135
telemt_desync_suppressed_total 291
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 178
telemt_desync_frames_bucket_total{bucket="gt_10"} 181
telemt_pool_swap_total 5
telemt_me_writer_close_signal_drop_total 43
telemt_me_writer_removed_unexpected_total 1042
telemt_me_writer_restored_same_endpoint_total 1062
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 179
telemt_me_async_recovery_trigger_total 1239
telemt_user_connections_total{user="hello"} 155248
telemt_user_connections_current{user="hello"} 1039
telemt_user_octets_from_client{user="hello"} 2226139264 (2.07 GB)
telemt_user_octets_to_client{user="hello"} 39724082126 (37.00 GB)
telemt_user_msgs_from_client{user="hello"} 7378
telemt_user_msgs_to_client{user="hello"} 12667
telemt_user_unique_ips_current{user="hello"} 373
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 7869.5 (2h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 538760
telemt_connections_bad_total 36893
telemt_connections_current 3208
telemt_connections_me_current 3208
telemt_handshake_timeouts_total 9936
telemt_upstream_connect_attempt_total 1255
telemt_upstream_connect_success_total 1245
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 684
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 557
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 826
telemt_me_reconnect_success_total 812
telemt_me_reader_eof_total 839
telemt_me_idle_close_by_peer_total 839
telemt_me_route_drop_no_conn_total 189847
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 464087
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2490
telemt_desync_full_logged_total 754
telemt_desync_suppressed_total 1736
telemt_desync_frames_bucket_total{bucket="1_2"} 478
telemt_desync_frames_bucket_total{bucket="3_10"} 820
telemt_desync_frames_bucket_total{bucket="gt_10"} 1192
telemt_pool_swap_total 6
telemt_me_writer_close_signal_drop_total 25
telemt_me_writer_removed_unexpected_total 838
telemt_me_writer_restored_same_endpoint_total 795
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 463727
telemt_user_connections_current{user="hello"} 3208
telemt_user_octets_from_client{user="hello"} 6457296912 (6.01 GB)
telemt_user_octets_to_client{user="hello"} 195527728080 (182.10 GB)
telemt_user_unique_ips_current{user="hello"} 1044
telemt_user_unique_ips_recent_window{user="hello"} 495
```