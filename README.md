# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
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

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
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

# Server Metrics 2026-03-22 19:08:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 79344.1 (22h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2940234
telemt_connections_bad_total 187505
telemt_connections_current 1687
telemt_connections_me_current 1687
telemt_handshake_timeouts_total 97597
telemt_upstream_connect_attempt_total 29015
telemt_upstream_connect_success_total 29014
telemt_upstream_connect_attempts_per_request{bucket="1"} 29014
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18827
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 69
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 1176
telemt_me_reconnect_success_total 492
telemt_me_reader_eof_total 496
telemt_me_idle_close_by_peer_total 496
telemt_me_route_drop_no_conn_total 2562073
telemt_me_route_drop_channel_closed_total 1042
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2494394
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 537
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 616
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 10922
telemt_desync_full_logged_total 3469
telemt_desync_suppressed_total 7453
telemt_desync_frames_bucket_total{bucket="1_2"} 2931
telemt_desync_frames_bucket_total{bucket="3_10"} 4054
telemt_desync_frames_bucket_total{bucket="gt_10"} 3937
telemt_pool_swap_total 88
telemt_pool_force_close_total 2709
telemt_pool_stale_pick_total 22
telemt_me_writer_close_signal_drop_total 563
telemt_me_draining_writers_reap_progress_total 26497
telemt_me_writer_removed_unexpected_total 481
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1927
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24793
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2656
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23788
telemt_me_writer_teardown_success_total{mode="normal"} 26720
telemt_me_writer_teardown_noop_total 26507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53227
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 287.156947
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53227
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 563
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 434
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 2488500
telemt_user_connections_current{user="hello"} 1687
telemt_user_octets_from_client{user="hello"} 36281010356 (33.79 GB)
telemt_user_octets_to_client{user="hello"} 653546808348 (608.66 GB)
telemt_user_unique_ips_current{user="hello"} 534
telemt_user_unique_ips_recent_window{user="hello"} 277
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 92710.2 (25h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3787914
telemt_connections_bad_total 339013
telemt_connections_current 1041
telemt_connections_me_current 1041
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 96811
telemt_upstream_connect_attempt_total 56364
telemt_upstream_connect_success_total 55675
telemt_upstream_connect_fail_total 607
telemt_upstream_connect_attempts_per_request{bucket="1"} 56282
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31582
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23914
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 179
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 607
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6386
telemt_me_reconnect_success_total 2343
telemt_me_reader_eof_total 2277
telemt_me_idle_close_by_peer_total 2277
telemt_me_route_drop_no_conn_total 3591169
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3011418
telemt_me_endpoint_quarantine_total 720
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 715
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 12010
telemt_desync_full_logged_total 6716
telemt_desync_suppressed_total 5294
telemt_desync_frames_bucket_total{bucket="1_2"} 2768
telemt_desync_frames_bucket_total{bucket="3_10"} 4693
telemt_desync_frames_bucket_total{bucket="gt_10"} 4549
telemt_pool_swap_total 87
telemt_pool_force_close_total 2630
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 223
telemt_me_draining_writers_reap_progress_total 36786
telemt_me_writer_removed_unexpected_total 2227
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4334
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34691
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2241
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 389
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34156
telemt_me_writer_teardown_success_total{mode="normal"} 39025
telemt_me_writer_teardown_noop_total 36786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75811
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.856195
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75811
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 223
telemt_me_refill_failed_total 161
telemt_me_writer_restored_same_endpoint_total 2030
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 3022228
telemt_user_connections_current{user="hello"} 1041
telemt_user_octets_from_client{user="hello"} 39163324991 (36.47 GB)
telemt_user_octets_to_client{user="hello"} 708564549814 (659.90 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 614
telemt_user_unique_ips_recent_window{user="hello"} 203
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 167570.1 (46h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15818335
telemt_connections_bad_total 1523581
telemt_connections_current 2267
telemt_connections_me_current 2267
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 390452
telemt_upstream_connect_attempt_total 74764
telemt_upstream_connect_success_total 74667
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 74684
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37280
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35696
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1684
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2769
telemt_me_reconnect_success_total 1424
telemt_me_reader_eof_total 1365
telemt_me_idle_close_by_peer_total 1363
telemt_me_route_drop_no_conn_total 13938367
telemt_me_route_drop_channel_closed_total 142
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12605611
telemt_me_endpoint_quarantine_total 1061
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1250
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 52019
telemt_desync_full_logged_total 16353
telemt_desync_suppressed_total 35666
telemt_desync_frames_bucket_total{bucket="1_2"} 11606
telemt_desync_frames_bucket_total{bucket="3_10"} 20261
telemt_desync_frames_bucket_total{bucket="gt_10"} 20152
telemt_pool_swap_total 181
telemt_pool_force_close_total 6089
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 988
telemt_me_draining_writers_reap_progress_total 55016
telemt_me_writer_removed_unexpected_total 1317
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4822
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50804
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5621
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 468
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48927
telemt_me_writer_teardown_success_total{mode="normal"} 55626
telemt_me_writer_teardown_noop_total 55066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 109078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 110653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 110683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 110684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 110688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 110690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 110692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 110692
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 308.072994
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 110692
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 988
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 1228
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 12606228
telemt_user_connections_current{user="hello"} 2267
telemt_user_octets_from_client{user="hello"} 183658137849 (171.04 GB)
telemt_user_octets_to_client{user="hello"} 3322076065723 (3.02 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 943
telemt_user_unique_ips_recent_window{user="hello"} 247
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 167571.4 (46h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11420541
telemt_connections_bad_total 1130124
telemt_connections_current 1470
telemt_connections_me_current 1470
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 340137
telemt_upstream_connect_attempt_total 87259
telemt_upstream_connect_success_total 86034
telemt_upstream_connect_fail_total 843
telemt_upstream_connect_attempts_per_request{bucket="1"} 86877
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46544
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35608
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 174
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3708
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 843
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4122
telemt_me_reconnect_success_total 1701
telemt_me_reader_eof_total 1571
telemt_me_idle_close_by_peer_total 1571
telemt_me_route_drop_no_conn_total 4466125
telemt_me_route_drop_channel_closed_total 491
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8511009
telemt_me_endpoint_quarantine_total 1059
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1269
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 37732
telemt_desync_full_logged_total 12717
telemt_desync_suppressed_total 25015
telemt_desync_frames_bucket_total{bucket="1_2"} 9307
telemt_desync_frames_bucket_total{bucket="3_10"} 14539
telemt_desync_frames_bucket_total{bucket="gt_10"} 13886
telemt_pool_swap_total 178
telemt_pool_force_close_total 5498
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 696
telemt_me_draining_writers_reap_progress_total 53468
telemt_me_writer_removed_unexpected_total 1609
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4938
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49985
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4997
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 501
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47970
telemt_me_writer_teardown_success_total{mode="normal"} 54923
telemt_me_writer_teardown_noop_total 53491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108414
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 103.197022
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108414
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 696
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 1457
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 8449363
telemt_user_connections_current{user="hello"} 1470
telemt_user_octets_from_client{user="hello"} 211146278325 (196.65 GB)
telemt_user_octets_to_client{user="hello"} 3810583109562 (3.47 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 581
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 167535.5 (46h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10741215
telemt_connections_bad_total 925297
telemt_connections_current 1362
telemt_connections_me_current 1362
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 342859
telemt_upstream_connect_attempt_total 72310
telemt_upstream_connect_success_total 71249
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 71433
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33551
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34036
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1520
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_keepalive_timeout_total 1385
telemt_me_reconnect_attempts_total 4924
telemt_me_reconnect_success_total 1983
telemt_me_reader_eof_total 1733
telemt_me_idle_close_by_peer_total 1732
telemt_me_route_drop_no_conn_total 5234694
telemt_me_route_drop_channel_closed_total 371
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8118467
telemt_me_endpoint_quarantine_total 1144
telemt_me_single_endpoint_outage_enter_total 33
telemt_me_single_endpoint_outage_exit_total 33
telemt_me_single_endpoint_outage_reconnect_attempt_total 34
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 34
telemt_me_single_endpoint_shadow_rotate_total 1228
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 59
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 42
telemt_desync_total 37280
telemt_desync_full_logged_total 12329
telemt_desync_suppressed_total 24951
telemt_desync_frames_bucket_total{bucket="1_2"} 9433
telemt_desync_frames_bucket_total{bucket="3_10"} 14272
telemt_desync_frames_bucket_total{bucket="gt_10"} 13575
telemt_pool_swap_total 176
telemt_pool_force_close_total 5438
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 704
telemt_me_draining_writers_reap_progress_total 53605
telemt_me_writer_removed_unexpected_total 1874
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5376
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50020
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4890
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 548
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48167
telemt_me_writer_teardown_success_total{mode="normal"} 55396
telemt_me_writer_teardown_noop_total 53676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 106007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109072
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3173.646526
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109072
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 704
telemt_me_refill_failed_total 156
telemt_me_writer_restored_same_endpoint_total 1709
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 152
telemt_user_connections_total{user="hello"} 8110906
telemt_user_connections_current{user="hello"} 1362
telemt_user_octets_from_client{user="hello"} 188034487233 (175.12 GB)
telemt_user_octets_to_client{user="hello"} 3376982801333 (3.07 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 528
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 37815.5 (10h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10675859
telemt_connections_bad_total 651714
telemt_connections_current 2129
telemt_connections_me_current 2129
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 223883
telemt_upstream_connect_attempt_total 44078
telemt_upstream_connect_success_total 41856
telemt_upstream_connect_fail_total 1538
telemt_upstream_connect_attempts_per_request{bucket="1"} 43394
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21436
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13009
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5951
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1538
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6393
telemt_me_reconnect_success_total 863
telemt_me_reader_eof_total 532
telemt_me_idle_close_by_peer_total 532
telemt_me_route_drop_no_conn_total 25148417
telemt_me_route_drop_channel_closed_total 53
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8866514
telemt_me_endpoint_quarantine_total 235
telemt_me_single_endpoint_outage_enter_total 63
telemt_me_single_endpoint_outage_exit_total 63
telemt_me_single_endpoint_outage_reconnect_attempt_total 114
telemt_me_single_endpoint_outage_reconnect_success_total 34
telemt_me_single_endpoint_quarantine_bypass_total 114
telemt_me_single_endpoint_shadow_rotate_total 295
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 14298
telemt_desync_full_logged_total 3735
telemt_desync_suppressed_total 10563
telemt_desync_frames_bucket_total{bucket="1_2"} 2643
telemt_desync_frames_bucket_total{bucket="3_10"} 5801
telemt_desync_frames_bucket_total{bucket="gt_10"} 5854
telemt_pool_swap_total 37
telemt_pool_force_close_total 1372
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 416
telemt_me_draining_writers_reap_progress_total 10670
telemt_me_writer_removed_unexpected_total 776
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1623
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9783
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1083
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 289
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9298
telemt_me_writer_teardown_success_total{mode="normal"} 11406
telemt_me_writer_teardown_noop_total 10689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 18853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 20320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 20860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 21580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 21921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 22039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 22095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 22095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 22095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 22095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 22095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 22095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 22095
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 47.866747
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 22095
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 416
telemt_me_refill_failed_total 306
telemt_me_writer_restored_same_endpoint_total 574
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 198
telemt_user_connections_total{user="hello"} 8888773
telemt_user_connections_current{user="hello"} 2129
telemt_user_octets_from_client{user="hello"} 81084406447 (75.52 GB)
telemt_user_octets_to_client{user="hello"} 444720425971 (414.18 GB)
telemt_user_msgs_from_client{user="hello"} 58278
telemt_user_msgs_to_client{user="hello"} 46361
telemt_user_unique_ips_current{user="hello"} 765
telemt_user_unique_ips_recent_window{user="hello"} 285
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 167542.2 (46h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10601258
telemt_connections_bad_total 893130
telemt_connections_current 1692
telemt_connections_me_current 1692
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 233466
telemt_upstream_connect_attempt_total 101362
telemt_upstream_connect_success_total 100285
telemt_upstream_connect_fail_total 917
telemt_upstream_connect_attempts_per_request{bucket="1"} 101202
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61320
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37397
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1330
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 917
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72244
telemt_me_reconnect_success_total 2755
telemt_me_reader_eof_total 2445
telemt_me_idle_close_by_peer_total 2443
telemt_me_route_drop_no_conn_total 5167530
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8371253
telemt_me_endpoint_quarantine_total 1110
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 1248
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 51
telemt_me_writers_warm_current 34
telemt_desync_total 44502
telemt_desync_full_logged_total 15151
telemt_desync_suppressed_total 29351
telemt_desync_frames_bucket_total{bucket="1_2"} 9024
telemt_desync_frames_bucket_total{bucket="3_10"} 17072
telemt_desync_frames_bucket_total{bucket="gt_10"} 18406
telemt_pool_swap_total 171
telemt_pool_force_close_total 5090
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 627
telemt_me_draining_writers_reap_progress_total 57045
telemt_me_writer_removed_unexpected_total 2483
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6071
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53483
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4393
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 697
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51955
telemt_me_writer_teardown_success_total{mode="normal"} 59554
telemt_me_writer_teardown_noop_total 57046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 114521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 115873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 116283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 116556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 116590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 116593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 116593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 116596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 116600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 116600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 116600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 116600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 116600
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.919745
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 116600
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 627
telemt_me_refill_failed_total 4281
telemt_me_writer_restored_same_endpoint_total 2308
telemt_me_writer_restored_fallback_total 47
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 128
telemt_user_connections_total{user="hello"} 8374721
telemt_user_connections_current{user="hello"} 1692
telemt_user_octets_from_client{user="hello"} 190098060217 (177.04 GB)
telemt_user_octets_to_client{user="hello"} 3178740428856 (2.89 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 691
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 104378.3 (28h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11144505
telemt_connections_bad_total 434760
telemt_connections_current 1494
telemt_connections_me_current 1494
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4608209
telemt_upstream_connect_attempt_total 49608
telemt_upstream_connect_success_total 49242
telemt_upstream_connect_fail_total 357
telemt_upstream_connect_attempts_per_request{bucket="1"} 49599
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21895
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 357
telemt_me_reconnect_attempts_total 48306
telemt_me_reconnect_success_total 1637
telemt_me_reader_eof_total 1296
telemt_me_idle_close_by_peer_total 1295
telemt_me_route_drop_no_conn_total 4012107
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5363822
telemt_me_endpoint_quarantine_total 674
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 785
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 47
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 30044
telemt_desync_full_logged_total 10154
telemt_desync_suppressed_total 19890
telemt_desync_frames_bucket_total{bucket="1_2"} 6032
telemt_desync_frames_bucket_total{bucket="3_10"} 11875
telemt_desync_frames_bucket_total{bucket="gt_10"} 12137
telemt_pool_swap_total 109
telemt_pool_force_close_total 3348
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 343
telemt_me_draining_writers_reap_progress_total 36166
telemt_me_writer_removed_unexpected_total 1357
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3226
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34330
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2909
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32818
telemt_me_writer_teardown_success_total{mode="normal"} 37556
telemt_me_writer_teardown_noop_total 36173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73729
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.325684
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73729
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 343
telemt_me_refill_failed_total 2712
telemt_me_writer_restored_same_endpoint_total 1461
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4330
telemt_user_connections_total{user="hello"} 5356798
telemt_user_connections_current{user="hello"} 1494
telemt_user_octets_from_client{user="hello"} 115711671088 (107.76 GB)
telemt_user_octets_to_client{user="hello"} 2049438422082 (1.86 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 582
telemt_user_unique_ips_recent_window{user="hello"} 191
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 85349.3 (23h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1263076
telemt_connections_bad_total 27838
telemt_connections_current 1090
telemt_connections_me_current 1090
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 24244
telemt_upstream_connect_attempt_total 40720
telemt_upstream_connect_success_total 40599
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 40693
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21597
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 676
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 1846
telemt_me_reconnect_success_total 785
telemt_me_reader_eof_total 758
telemt_me_idle_close_by_peer_total 758
telemt_me_route_drop_no_conn_total 441103
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1119296
telemt_me_endpoint_quarantine_total 713
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 702
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 6548
telemt_desync_full_logged_total 2017
telemt_desync_suppressed_total 4531
telemt_desync_frames_bucket_total{bucket="1_2"} 1479
telemt_desync_frames_bucket_total{bucket="3_10"} 2584
telemt_desync_frames_bucket_total{bucket="gt_10"} 2485
telemt_pool_swap_total 91
telemt_pool_force_close_total 2351
telemt_me_writer_close_signal_drop_total 137
telemt_me_draining_writers_reap_progress_total 33856
telemt_me_writer_removed_unexpected_total 732
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2653
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31964
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2266
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31505
telemt_me_writer_teardown_success_total{mode="normal"} 34617
telemt_me_writer_teardown_noop_total 33860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68477
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.193240
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68477
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 137
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 664
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 1115503
telemt_user_connections_current{user="hello"} 1090
telemt_user_octets_from_client{user="hello"} 21381598645 (19.91 GB)
telemt_user_octets_to_client{user="hello"} 474006433995 (441.45 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 406
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 167546.6 (46h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12916155
telemt_connections_bad_total 1508886
telemt_connections_current 1849
telemt_connections_me_current 1849
telemt_handshake_timeouts_total 366935
telemt_upstream_connect_attempt_total 63123
telemt_upstream_connect_success_total 62794
telemt_upstream_connect_fail_total 194
telemt_upstream_connect_attempts_per_request{bucket="1"} 62988
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31010
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31684
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 194
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2459
telemt_me_reconnect_success_total 1303
telemt_me_reader_eof_total 1266
telemt_me_idle_close_by_peer_total 1266
telemt_me_route_drop_no_conn_total 4391626
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9770964
telemt_me_endpoint_quarantine_total 1122
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1250
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 40211
telemt_desync_full_logged_total 13106
telemt_desync_suppressed_total 27105
telemt_desync_frames_bucket_total{bucket="1_2"} 9607
telemt_desync_frames_bucket_total{bucket="3_10"} 14843
telemt_desync_frames_bucket_total{bucket="gt_10"} 15761
telemt_pool_swap_total 186
telemt_pool_force_close_total 5098
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 643
telemt_me_draining_writers_reap_progress_total 56835
telemt_me_writer_removed_unexpected_total 1218
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4661
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53430
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4924
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51737
telemt_me_writer_teardown_success_total{mode="normal"} 58091
telemt_me_writer_teardown_noop_total 56837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 112439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 114067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 114434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 114795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 114915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 114928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 114928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 114928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 114928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 114928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 114928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 114928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 114928
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.111082
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 114928
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 643
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 1139
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 9738867
telemt_user_connections_current{user="hello"} 1849
telemt_user_octets_from_client{user="hello"} 190773282716 (177.67 GB)
telemt_user_octets_to_client{user="hello"} 4299871921700 (3.91 TB)
telemt_user_unique_ips_current{user="hello"} 673
telemt_user_unique_ips_recent_window{user="hello"} 199
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 167543.4 (46h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11226529
telemt_connections_bad_total 1273917
telemt_connections_current 1506
telemt_connections_me_current 1506
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 294666
telemt_upstream_connect_attempt_total 89487
telemt_upstream_connect_success_total 88674
telemt_upstream_connect_fail_total 606
telemt_upstream_connect_attempts_per_request{bucket="1"} 89280
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48580
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37116
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 606
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 9651
telemt_me_reconnect_success_total 2308
telemt_me_reader_eof_total 2153
telemt_me_idle_close_by_peer_total 2152
telemt_me_seq_mismatch_total 78
telemt_me_route_drop_no_conn_total 5570474
telemt_me_route_drop_channel_closed_total 353
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8673191
telemt_me_endpoint_quarantine_total 1287
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 45
telemt_me_single_endpoint_outage_exit_total 45
telemt_me_single_endpoint_outage_reconnect_attempt_total 45
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 45
telemt_me_single_endpoint_shadow_rotate_total 1250
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 39601
telemt_desync_full_logged_total 12794
telemt_desync_suppressed_total 26807
telemt_desync_frames_bucket_total{bucket="1_2"} 9886
telemt_desync_frames_bucket_total{bucket="3_10"} 14725
telemt_desync_frames_bucket_total{bucket="gt_10"} 14990
telemt_pool_swap_total 176
telemt_pool_force_close_total 4899
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 634
telemt_me_draining_writers_reap_progress_total 56575
telemt_me_writer_removed_unexpected_total 2187
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5984
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52851
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4428
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51676
telemt_me_writer_teardown_success_total{mode="normal"} 58835
telemt_me_writer_teardown_noop_total 56580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 112795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 114510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 115046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 115365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 115415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 115415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 115415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 115415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 115415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 115415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 115415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 115415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 115415
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.098115
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 115415
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 634
telemt_me_refill_failed_total 379
telemt_me_writer_restored_same_endpoint_total 1883
telemt_me_writer_restored_fallback_total 106
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 198
telemt_user_connections_total{user="hello"} 8678877
telemt_user_connections_current{user="hello"} 1506
telemt_user_octets_from_client{user="hello"} 152985528749 (142.48 GB)
telemt_user_octets_to_client{user="hello"} 3339418987091 (3.04 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 577
telemt_user_unique_ips_recent_window{user="hello"} 171
```