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

# Server Metrics 2026-03-23 01:46:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 103211.0 (28h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3563810
telemt_connections_bad_total 322968
telemt_connections_current 850
telemt_connections_me_current 850
telemt_handshake_timeouts_total 111835
telemt_upstream_connect_attempt_total 38464
telemt_upstream_connect_success_total 38463
telemt_upstream_connect_attempts_per_request{bucket="1"} 38463
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13349
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24980
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1409
telemt_me_reconnect_success_total 612
telemt_me_reader_eof_total 629
telemt_me_idle_close_by_peer_total 629
telemt_me_route_drop_no_conn_total 2990678
telemt_me_route_drop_channel_closed_total 1234
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2934407
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 727
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 806
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_me_writers_active_current 44
telemt_desync_total 12616
telemt_desync_full_logged_total 3970
telemt_desync_suppressed_total 8646
telemt_desync_frames_bucket_total{bucket="1_2"} 3379
telemt_desync_frames_bucket_total{bucket="3_10"} 4597
telemt_desync_frames_bucket_total{bucket="gt_10"} 4640
telemt_pool_swap_total 114
telemt_pool_force_close_total 3503
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 660
telemt_me_draining_writers_reap_progress_total 35216
telemt_me_writer_removed_unexpected_total 606
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2519
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32952
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3447
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31713
telemt_me_writer_teardown_success_total{mode="normal"} 35471
telemt_me_writer_teardown_noop_total 35227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70698
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 378.726115
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70698
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 660
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 548
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 2923418
telemt_user_connections_current{user="hello"} 850
telemt_user_octets_from_client{user="hello"} 41737281104 (38.87 GB)
telemt_user_octets_to_client{user="hello"} 801051019404 (746.04 GB)
telemt_user_unique_ips_current{user="hello"} 422
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 116577.6 (32h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4010933
telemt_connections_bad_total 370503
telemt_connections_current 235
telemt_connections_me_current 235
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 100879
telemt_upstream_connect_attempt_total 72678
telemt_upstream_connect_success_total 71792
telemt_upstream_connect_fail_total 781
telemt_upstream_connect_attempts_per_request{bucket="1"} 72573
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39949
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31630
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 213
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 781
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10170
telemt_me_reconnect_success_total 3660
telemt_me_reader_eof_total 3648
telemt_me_idle_close_by_peer_total 3648
telemt_me_route_drop_no_conn_total 3642059
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3186204
telemt_me_endpoint_quarantine_total 938
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 45
telemt_me_single_endpoint_outage_exit_total 45
telemt_me_single_endpoint_outage_reconnect_attempt_total 45
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 45
telemt_me_single_endpoint_shadow_rotate_total 913
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 12987
telemt_desync_full_logged_total 7286
telemt_desync_suppressed_total 5701
telemt_desync_frames_bucket_total{bucket="1_2"} 2946
telemt_desync_frames_bucket_total{bucket="3_10"} 5096
telemt_desync_frames_bucket_total{bucket="gt_10"} 4945
telemt_pool_swap_total 109
telemt_pool_force_close_total 3119
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 254
telemt_me_draining_writers_reap_progress_total 48091
telemt_me_writer_removed_unexpected_total 3577
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6291
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45411
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2661
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44972
telemt_me_writer_teardown_success_total{mode="normal"} 51702
telemt_me_writer_teardown_noop_total 48092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99794
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.632872
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99794
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 254
telemt_me_refill_failed_total 252
telemt_me_writer_restored_same_endpoint_total 3259
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 3199501
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 43195534595 (40.23 GB)
telemt_user_octets_to_client{user="hello"} 793618712060 (739.12 GB)
telemt_user_msgs_from_client{user="hello"} 49657
telemt_user_msgs_to_client{user="hello"} 185005
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 191437.8 (53h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16364283
telemt_connections_bad_total 1657815
telemt_connections_current 856
telemt_connections_me_current 856
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 397945
telemt_upstream_connect_attempt_total 85929
telemt_upstream_connect_success_total 85823
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 85840
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42027
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42067
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1722
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3018
telemt_me_reconnect_success_total 1594
telemt_me_reader_eof_total 1543
telemt_me_idle_close_by_peer_total 1541
telemt_me_route_drop_no_conn_total 14049421
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12993200
telemt_me_endpoint_quarantine_total 1278
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1441
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_desync_total 53909
telemt_desync_full_logged_total 17133
telemt_desync_suppressed_total 36776
telemt_desync_frames_bucket_total{bucket="1_2"} 12017
telemt_desync_frames_bucket_total{bucket="3_10"} 21049
telemt_desync_frames_bucket_total{bucket="gt_10"} 20843
telemt_pool_swap_total 207
telemt_pool_force_close_total 6763
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1064
telemt_me_draining_writers_reap_progress_total 65257
telemt_me_writer_removed_unexpected_total 1484
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5553
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60466
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6293
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58494
telemt_me_writer_teardown_success_total{mode="normal"} 66019
telemt_me_writer_teardown_noop_total 65310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 120165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 123833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 125609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 128001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 129668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 130719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 131290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 131320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 131321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 131325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 131327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 131329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 131329
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.810563
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 131329
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1064
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1379
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 12993214
telemt_user_connections_current{user="hello"} 856
telemt_user_octets_from_client{user="hello"} 195817338589 (182.37 GB)
telemt_user_octets_to_client{user="hello"} 3496923799079 (3.18 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 419
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 191438.9 (53h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11905980
telemt_connections_bad_total 1239857
telemt_connections_current 577
telemt_connections_me_current 577
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344677
telemt_upstream_connect_attempt_total 100285
telemt_upstream_connect_success_total 98957
telemt_upstream_connect_fail_total 875
telemt_upstream_connect_attempts_per_request{bucket="1"} 99832
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53004
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41964
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3801
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 875
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4444
telemt_me_reconnect_success_total 1894
telemt_me_reader_eof_total 1761
telemt_me_idle_close_by_peer_total 1761
telemt_me_route_drop_no_conn_total 4558968
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8834815
telemt_me_endpoint_quarantine_total 1286
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1461
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
telemt_me_writers_active_current 44
telemt_desync_total 38933
telemt_desync_full_logged_total 13112
telemt_desync_suppressed_total 25821
telemt_desync_frames_bucket_total{bucket="1_2"} 9649
telemt_desync_frames_bucket_total{bucket="3_10"} 14947
telemt_desync_frames_bucket_total{bucket="gt_10"} 14337
telemt_pool_swap_total 204
telemt_pool_force_close_total 6119
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 711
telemt_me_draining_writers_reap_progress_total 63490
telemt_me_writer_removed_unexpected_total 1790
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5635
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59502
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5607
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57371
telemt_me_writer_teardown_success_total{mode="normal"} 65137
telemt_me_writer_teardown_noop_total 63515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 121902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 125128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 126277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 127468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 128227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 128567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 128642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 128644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 128650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 128652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 128652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 128652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 128652
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.446801
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 128652
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 711
telemt_me_refill_failed_total 137
telemt_me_writer_restored_same_endpoint_total 1621
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 149
telemt_user_connections_total{user="hello"} 8772568
telemt_user_connections_current{user="hello"} 577
telemt_user_octets_from_client{user="hello"} 217966266800 (203.00 GB)
telemt_user_octets_to_client{user="hello"} 3967544142199 (3.61 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 260
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 191402.9 (53h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11075544
telemt_connections_bad_total 978368
telemt_connections_current 546
telemt_connections_me_current 546
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345652
telemt_upstream_connect_attempt_total 84603
telemt_upstream_connect_success_total 83044
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 83249
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38248
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40401
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2032
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2363
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5768
telemt_me_reconnect_success_total 2388
telemt_me_reader_eof_total 2133
telemt_me_idle_close_by_peer_total 2132
telemt_me_route_drop_no_conn_total 5339852
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8370360
telemt_me_endpoint_quarantine_total 1345
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1419
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 69
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
telemt_desync_total 38213
telemt_desync_full_logged_total 12657
telemt_desync_suppressed_total 25556
telemt_desync_frames_bucket_total{bucket="1_2"} 9652
telemt_desync_frames_bucket_total{bucket="3_10"} 14623
telemt_desync_frames_bucket_total{bucket="gt_10"} 13938
telemt_pool_swap_total 200
telemt_pool_force_close_total 6019
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 743
telemt_me_draining_writers_reap_progress_total 63873
telemt_me_writer_removed_unexpected_total 2283
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6396
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59692
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5448
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57854
telemt_me_writer_teardown_success_total{mode="normal"} 66088
telemt_me_writer_teardown_noop_total 63944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 124194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 126914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 127877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 128950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 129551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 129765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 129893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 129924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 129932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 129945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 129978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 129981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 130032
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.821952
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 130032
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 743
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 2078
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 8362313
telemt_user_connections_current{user="hello"} 546
telemt_user_octets_from_client{user="hello"} 192829398571 (179.59 GB)
telemt_user_octets_to_client{user="hello"} 3474248345265 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 254
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 61683.0 (17h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11283751
telemt_connections_bad_total 669278
telemt_connections_current 1005
telemt_connections_me_current 1005
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 277623
telemt_upstream_connect_attempt_total 59000
telemt_upstream_connect_success_total 55909
telemt_upstream_connect_fail_total 2036
telemt_upstream_connect_attempts_per_request{bucket="1"} 57945
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28832
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19542
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6018
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2036
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7799
telemt_me_reconnect_success_total 1269
telemt_me_reader_eof_total 799
telemt_me_idle_close_by_peer_total 798
telemt_me_route_drop_no_conn_total 25295243
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9359049
telemt_me_endpoint_quarantine_total 457
telemt_me_single_endpoint_outage_enter_total 94
telemt_me_single_endpoint_outage_exit_total 94
telemt_me_single_endpoint_outage_reconnect_attempt_total 179
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 179
telemt_me_single_endpoint_shadow_rotate_total 492
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_desync_total 16414
telemt_desync_full_logged_total 4485
telemt_desync_suppressed_total 11929
telemt_desync_frames_bucket_total{bucket="1_2"} 3117
telemt_desync_frames_bucket_total{bucket="3_10"} 6690
telemt_desync_frames_bucket_total{bucket="gt_10"} 6607
telemt_pool_swap_total 64
telemt_pool_force_close_total 2065
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 490
telemt_me_draining_writers_reap_progress_total 19513
telemt_me_writer_removed_unexpected_total 1155
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2620
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17992
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1758
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17448
telemt_me_writer_teardown_success_total{mode="normal"} 20612
telemt_me_writer_teardown_noop_total 19532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40144
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.925170
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40144
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 490
telemt_me_refill_failed_total 340
telemt_me_writer_restored_same_endpoint_total 815
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 327
telemt_user_connections_total{user="hello"} 9384910
telemt_user_connections_current{user="hello"} 1005
telemt_user_octets_from_client{user="hello"} 87509674858 (81.50 GB)
telemt_user_octets_to_client{user="hello"} 616806408038 (574.45 GB)
telemt_user_msgs_from_client{user="hello"} 68321
telemt_user_msgs_to_client{user="hello"} 57932
telemt_user_unique_ips_current{user="hello"} 422
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 191409.4 (53h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11025500
telemt_connections_bad_total 961790
telemt_connections_current 739
telemt_connections_me_current 739
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 242546
telemt_upstream_connect_attempt_total 113434
telemt_upstream_connect_success_total 112265
telemt_upstream_connect_fail_total 995
telemt_upstream_connect_attempts_per_request{bucket="1"} 113260
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66742
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43921
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1364
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 995
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73020
telemt_me_reconnect_success_total 3105
telemt_me_reader_eof_total 2798
telemt_me_idle_close_by_peer_total 2796
telemt_me_route_drop_no_conn_total 5266194
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8691584
telemt_me_endpoint_quarantine_total 1299
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1448
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_me_writers_active_current 41
telemt_desync_total 46313
telemt_desync_full_logged_total 15879
telemt_desync_suppressed_total 30434
telemt_desync_frames_bucket_total{bucket="1_2"} 9411
telemt_desync_frames_bucket_total{bucket="3_10"} 17727
telemt_desync_frames_bucket_total{bucket="gt_10"} 19175
telemt_pool_swap_total 196
telemt_pool_force_close_total 5731
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 665
telemt_me_draining_writers_reap_progress_total 67950
telemt_me_writer_removed_unexpected_total 2822
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6915
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63897
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4982
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62219
telemt_me_writer_teardown_success_total{mode="normal"} 70812
telemt_me_writer_teardown_noop_total 67951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 136611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 138027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 138446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 138719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 138753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 138756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 138756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 138759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 138763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 138763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 138763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 138763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 138763
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.283376
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 138763
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 665
telemt_me_refill_failed_total 4303
telemt_me_writer_restored_same_endpoint_total 2618
telemt_me_writer_restored_fallback_total 52
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 152
telemt_user_connections_total{user="hello"} 8694531
telemt_user_connections_current{user="hello"} 739
telemt_user_octets_from_client{user="hello"} 194788656441 (181.41 GB)
telemt_user_octets_to_client{user="hello"} 3324517637712 (3.02 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 357
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 128245.7 (35h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11724233
telemt_connections_bad_total 482602
telemt_connections_current 516
telemt_connections_me_current 516
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4762767
telemt_upstream_connect_attempt_total 61916
telemt_upstream_connect_success_total 61460
telemt_upstream_connect_fail_total 444
telemt_upstream_connect_attempts_per_request{bucket="1"} 61904
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32773
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28465
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 444
telemt_me_reconnect_attempts_total 49060
telemt_me_reconnect_success_total 1844
telemt_me_reader_eof_total 1518
telemt_me_idle_close_by_peer_total 1517
telemt_me_route_drop_no_conn_total 4096162
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5635276
telemt_me_endpoint_quarantine_total 873
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 984
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31722
telemt_desync_full_logged_total 10830
telemt_desync_suppressed_total 20892
telemt_desync_frames_bucket_total{bucket="1_2"} 6316
telemt_desync_frames_bucket_total{bucket="3_10"} 12513
telemt_desync_frames_bucket_total{bucket="gt_10"} 12893
telemt_pool_swap_total 136
telemt_pool_force_close_total 3946
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 378
telemt_me_draining_writers_reap_progress_total 47357
telemt_me_writer_removed_unexpected_total 1566
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3859
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45110
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3505
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43411
telemt_me_writer_teardown_success_total{mode="normal"} 48969
telemt_me_writer_teardown_noop_total 47364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96333
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.709962
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96333
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 378
telemt_me_refill_failed_total 2743
telemt_me_writer_restored_same_endpoint_total 1630
telemt_me_writer_restored_fallback_total 29
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5627421
telemt_user_connections_current{user="hello"} 516
telemt_user_octets_from_client{user="hello"} 120039084796 (111.80 GB)
telemt_user_octets_to_client{user="hello"} 2184520247190 (1.99 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 109216.6 (30h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1537805
telemt_connections_bad_total 36784
telemt_connections_current 423
telemt_connections_me_current 423
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 31338
telemt_upstream_connect_attempt_total 51612
telemt_upstream_connect_success_total 51451
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 51584
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23877
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26780
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 794
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2288
telemt_me_reconnect_success_total 935
telemt_me_reader_eof_total 923
telemt_me_idle_close_by_peer_total 923
telemt_me_route_drop_no_conn_total 520330
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1367003
telemt_me_endpoint_quarantine_total 914
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 904
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 9217
telemt_desync_full_logged_total 2667
telemt_desync_suppressed_total 6550
telemt_desync_frames_bucket_total{bucket="1_2"} 2661
telemt_desync_frames_bucket_total{bucket="3_10"} 3507
telemt_desync_frames_bucket_total{bucket="gt_10"} 3049
telemt_pool_swap_total 118
telemt_pool_force_close_total 3003
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 171
telemt_me_draining_writers_reap_progress_total 43708
telemt_me_writer_removed_unexpected_total 889
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3347
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41291
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2915
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40705
telemt_me_writer_teardown_success_total{mode="normal"} 44638
telemt_me_writer_teardown_noop_total 43712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88350
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.351396
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88350
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 171
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 796
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 1362802
telemt_user_connections_current{user="hello"} 423
telemt_user_octets_from_client{user="hello"} 26138772437 (24.34 GB)
telemt_user_octets_to_client{user="hello"} 580295445487 (540.44 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 191414.1 (53h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13345789
telemt_connections_bad_total 1608102
telemt_connections_current 621
telemt_connections_me_current 621
telemt_handshake_timeouts_total 389858
telemt_upstream_connect_attempt_total 75803
telemt_upstream_connect_success_total 75451
telemt_upstream_connect_fail_total 216
telemt_upstream_connect_attempts_per_request{bucket="1"} 75667
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38061
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 216
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3025
telemt_me_reconnect_success_total 1506
telemt_me_reader_eof_total 1492
telemt_me_idle_close_by_peer_total 1492
telemt_me_route_drop_no_conn_total 4485106
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10060891
telemt_me_endpoint_quarantine_total 1381
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1449
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 42168
telemt_desync_full_logged_total 13771
telemt_desync_suppressed_total 28397
telemt_desync_frames_bucket_total{bucket="1_2"} 10230
telemt_desync_frames_bucket_total{bucket="3_10"} 15492
telemt_desync_frames_bucket_total{bucket="gt_10"} 16446
telemt_pool_swap_total 212
telemt_pool_force_close_total 5624
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 680
telemt_me_draining_writers_reap_progress_total 68560
telemt_me_writer_removed_unexpected_total 1429
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5368
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64674
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5450
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62936
telemt_me_writer_teardown_success_total{mode="normal"} 70042
telemt_me_writer_teardown_noop_total 68562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 135989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 137712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 138095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 138471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 138591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 138604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 138604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 138604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 138604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 138604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 138604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 138604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 138604
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.800418
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 138604
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 680
telemt_me_refill_failed_total 82
telemt_me_writer_restored_same_endpoint_total 1322
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 10027586
telemt_user_connections_current{user="hello"} 621
telemt_user_octets_from_client{user="hello"} 194888203040 (181.50 GB)
telemt_user_octets_to_client{user="hello"} 4443720215748 (4.04 TB)
telemt_user_unique_ips_current{user="hello"} 268
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 191410.5 (53h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11664438
telemt_connections_bad_total 1363492
telemt_connections_current 542
telemt_connections_me_current 542
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 311879
telemt_upstream_connect_attempt_total 103314
telemt_upstream_connect_success_total 102422
telemt_upstream_connect_fail_total 684
telemt_upstream_connect_attempts_per_request{bucket="1"} 103106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55810
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43631
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2068
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 684
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10521
telemt_me_reconnect_success_total 2613
telemt_me_reader_eof_total 2422
telemt_me_idle_close_by_peer_total 2421
telemt_me_seq_mismatch_total 100
telemt_me_route_drop_no_conn_total 5652677
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8974186
telemt_me_endpoint_quarantine_total 1558
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 52
telemt_me_single_endpoint_outage_exit_total 52
telemt_me_single_endpoint_outage_reconnect_attempt_total 52
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 52
telemt_me_single_endpoint_shadow_rotate_total 1452
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
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
telemt_me_writers_active_current 50
telemt_desync_total 41838
telemt_desync_full_logged_total 13473
telemt_desync_suppressed_total 28365
telemt_desync_frames_bucket_total{bucket="1_2"} 10808
telemt_desync_frames_bucket_total{bucket="3_10"} 15387
telemt_desync_frames_bucket_total{bucket="gt_10"} 15643
telemt_pool_swap_total 202
telemt_pool_force_close_total 5399
telemt_pool_stale_pick_total 372
telemt_me_writer_close_signal_drop_total 667
telemt_me_draining_writers_reap_progress_total 68582
telemt_me_writer_removed_unexpected_total 2465
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6745
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64388
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4928
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63183
telemt_me_writer_teardown_success_total{mode="normal"} 71133
telemt_me_writer_teardown_noop_total 68587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 137030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 138812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 139351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 139670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 139720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 139720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 139720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 139720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 139720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 139720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 139720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 139720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 139720
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.489003
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 139720
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 667
telemt_me_refill_failed_total 409
telemt_me_writer_restored_same_endpoint_total 2103
telemt_me_writer_restored_fallback_total 135
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 227
telemt_user_connections_total{user="hello"} 8978763
telemt_user_connections_current{user="hello"} 542
telemt_user_octets_from_client{user="hello"} 157493240256 (146.68 GB)
telemt_user_octets_to_client{user="hello"} 3494349082514 (3.18 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 258
telemt_user_unique_ips_recent_window{user="hello"} 55
```