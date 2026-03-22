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

# Server Metrics 2026-03-22 01:29:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 15788.5 (4h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 229416
telemt_connections_bad_total 16309
telemt_connections_current 747
telemt_connections_me_current 747
telemt_handshake_timeouts_total 13280
telemt_upstream_connect_attempt_total 6579
telemt_upstream_connect_success_total 6578
telemt_upstream_connect_attempts_per_request{bucket="1"} 6578
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2411
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4153
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 215
telemt_me_reconnect_success_total 107
telemt_me_reader_eof_total 103
telemt_me_idle_close_by_peer_total 103
telemt_me_route_drop_no_conn_total 43057
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 187153
telemt_me_endpoint_quarantine_total 122
telemt_me_single_endpoint_shadow_rotate_total 136
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_desync_total 1598
telemt_desync_full_logged_total 441
telemt_desync_suppressed_total 1157
telemt_desync_frames_bucket_total{bucket="1_2"} 499
telemt_desync_frames_bucket_total{bucket="3_10"} 582
telemt_desync_frames_bucket_total{bucket="gt_10"} 517
telemt_pool_swap_total 17
telemt_pool_force_close_total 444
telemt_me_writer_close_signal_drop_total 30
telemt_me_draining_writers_reap_progress_total 5905
telemt_me_writer_removed_unexpected_total 105
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 420
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5578
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5461
telemt_me_writer_teardown_success_total{mode="normal"} 5998
telemt_me_writer_teardown_noop_total 5906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 11564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 11766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 11832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 11878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 11902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 11904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 11904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 11904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 11904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 11904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 11904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 11904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 11904
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.901298
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 11904
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 30
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 97
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 186850
telemt_user_connections_current{user="hello"} 747
telemt_user_octets_from_client{user="hello"} 2042565128 (1.90 GB)
telemt_user_octets_to_client{user="hello"} 63222023180 (58.88 GB)
telemt_user_unique_ips_current{user="hello"} 351
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 29153.6 (8h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 736005
telemt_connections_bad_total 42487
telemt_connections_current 735
telemt_connections_me_current 735
telemt_handshake_timeouts_total 27543
telemt_upstream_connect_attempt_total 13020
telemt_upstream_connect_success_total 12805
telemt_upstream_connect_fail_total 195
telemt_upstream_connect_attempts_per_request{bucket="1"} 13000
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5709
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7056
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 195
telemt_me_reconnect_attempts_total 1132
telemt_me_reconnect_success_total 411
telemt_me_reader_eof_total 363
telemt_me_idle_close_by_peer_total 363
telemt_me_route_drop_no_conn_total 334511
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 589832
telemt_me_endpoint_quarantine_total 265
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 239
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
telemt_me_writers_active_current 91
telemt_desync_total 2583
telemt_desync_full_logged_total 1480
telemt_desync_suppressed_total 1103
telemt_desync_frames_bucket_total{bucket="1_2"} 552
telemt_desync_frames_bucket_total{bucket="3_10"} 976
telemt_desync_frames_bucket_total{bucket="gt_10"} 1055
telemt_pool_swap_total 31
telemt_pool_force_close_total 843
telemt_me_writer_close_signal_drop_total 61
telemt_me_draining_writers_reap_progress_total 11444
telemt_me_writer_removed_unexpected_total 345
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 999
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10795
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 836
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10601
telemt_me_writer_teardown_success_total{mode="normal"} 11794
telemt_me_writer_teardown_noop_total 11444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 22763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 23044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 23132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 23224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 23236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 23238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 23238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 23238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 23238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 23238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 23238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 23238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 23238
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.478679
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 23238
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 61
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 301
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 588965
telemt_user_connections_current{user="hello"} 735
telemt_user_octets_from_client{user="hello"} 9845380264 (9.17 GB)
telemt_user_octets_to_client{user="hello"} 211219857608 (196.71 GB)
telemt_user_unique_ips_current{user="hello"} 486
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 104013.4 (28h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7610810
telemt_connections_bad_total 617907
telemt_connections_current 1282
telemt_connections_me_current 1282
telemt_handshake_timeouts_total 248795
telemt_upstream_connect_attempt_total 38187
telemt_upstream_connect_success_total 38114
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 38121
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17264
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20681
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 163
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1546
telemt_me_reconnect_success_total 782
telemt_me_reader_eof_total 794
telemt_me_idle_close_by_peer_total 794
telemt_me_route_drop_no_conn_total 4519724
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6179739
telemt_me_endpoint_quarantine_total 664
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 777
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_desync_total 26199
telemt_desync_full_logged_total 8656
telemt_desync_suppressed_total 17543
telemt_desync_frames_bucket_total{bucket="1_2"} 5639
telemt_desync_frames_bucket_total{bucket="3_10"} 10217
telemt_desync_frames_bucket_total{bucket="gt_10"} 10343
telemt_pool_swap_total 112
telemt_pool_force_close_total 3760
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 593
telemt_me_draining_writers_reap_progress_total 34844
telemt_me_writer_removed_unexpected_total 763
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2921
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32230
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3521
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31084
telemt_me_writer_teardown_success_total{mode="normal"} 35151
telemt_me_writer_teardown_noop_total 34888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70039
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 156.941525
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70039
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 593
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 699
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 6171987
telemt_user_connections_current{user="hello"} 1282
telemt_user_octets_from_client{user="hello"} 105505850956 (98.26 GB)
telemt_user_octets_to_client{user="hello"} 2045588787632 (1.86 TB)
telemt_user_unique_ips_current{user="hello"} 727
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 104014.8 (28h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6265597
telemt_connections_bad_total 583480
telemt_connections_current 1443
telemt_connections_me_current 1443
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 208420
telemt_upstream_connect_attempt_total 42278
telemt_upstream_connect_success_total 41893
telemt_upstream_connect_fail_total 188
telemt_upstream_connect_attempts_per_request{bucket="1"} 42081
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20850
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20455
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 555
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 188
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1902
telemt_me_reconnect_success_total 849
telemt_me_reader_eof_total 818
telemt_me_idle_close_by_peer_total 818
telemt_me_route_drop_no_conn_total 2227552
telemt_me_route_drop_channel_closed_total 257
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4694532
telemt_me_endpoint_quarantine_total 644
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 799
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 22354
telemt_desync_full_logged_total 7594
telemt_desync_suppressed_total 14760
telemt_desync_frames_bucket_total{bucket="1_2"} 5381
telemt_desync_frames_bucket_total{bucket="3_10"} 8675
telemt_desync_frames_bucket_total{bucket="gt_10"} 8298
telemt_pool_swap_total 113
telemt_pool_force_close_total 3393
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 355
telemt_me_draining_writers_reap_progress_total 33446
telemt_me_writer_removed_unexpected_total 804
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2839
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31347
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3180
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30053
telemt_me_writer_teardown_success_total{mode="normal"} 34186
telemt_me_writer_teardown_noop_total 33452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67638
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.217636
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67638
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 355
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 741
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 4624058
telemt_user_connections_current{user="hello"} 1443
telemt_user_octets_from_client{user="hello"} 139397710905 (129.82 GB)
telemt_user_octets_to_client{user="hello"} 2173051370323 (1.98 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 715
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 103979.4 (28h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6162285
telemt_connections_bad_total 544945
telemt_connections_current 1310
telemt_connections_me_current 1310
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 197130
telemt_upstream_connect_attempt_total 48551
telemt_upstream_connect_success_total 48205
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 48341
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24933
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21802
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 412
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1058
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1944
telemt_me_reconnect_success_total 871
telemt_me_reader_eof_total 815
telemt_me_idle_close_by_peer_total 815
telemt_me_route_drop_no_conn_total 2124879
telemt_me_route_drop_channel_closed_total 116
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4591319
telemt_me_endpoint_quarantine_total 723
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 780
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_desync_total 22159
telemt_desync_full_logged_total 7423
telemt_desync_suppressed_total 14736
telemt_desync_frames_bucket_total{bucket="1_2"} 5412
telemt_desync_frames_bucket_total{bucket="3_10"} 8488
telemt_desync_frames_bucket_total{bucket="gt_10"} 8259
telemt_pool_swap_total 112
telemt_pool_force_close_total 3270
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 379
telemt_me_draining_writers_reap_progress_total 34769
telemt_me_writer_removed_unexpected_total 788
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2891
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32679
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3055
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31499
telemt_me_writer_teardown_success_total{mode="normal"} 35570
telemt_me_writer_teardown_noop_total 34780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70350
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.711032
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70350
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 379
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 755
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 4591878
telemt_user_connections_current{user="hello"} 1310
telemt_user_octets_from_client{user="hello"} 132827217415 (123.70 GB)
telemt_user_octets_to_client{user="hello"} 2097198721447 (1.91 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 675
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 104018.4 (28h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20221962
telemt_connections_bad_total 1555872
telemt_connections_current 1760
telemt_connections_me_current 1760
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 593076
telemt_upstream_connect_attempt_total 193644
telemt_upstream_connect_success_total 175735
telemt_upstream_connect_fail_total 16216
telemt_upstream_connect_attempts_per_request{bucket="1"} 191951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 124136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41469
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8909
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16216
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64762
telemt_me_reconnect_success_total 2267
telemt_me_reader_eof_total 1403
telemt_me_idle_close_by_peer_total 1402
telemt_me_route_drop_no_conn_total 39484014
telemt_me_route_drop_channel_closed_total 124
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16396388
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 809
telemt_me_single_endpoint_outage_enter_total 133
telemt_me_single_endpoint_outage_exit_total 133
telemt_me_single_endpoint_outage_reconnect_attempt_total 283
telemt_me_single_endpoint_outage_reconnect_success_total 68
telemt_me_single_endpoint_quarantine_bypass_total 283
telemt_me_single_endpoint_shadow_rotate_total 817
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 43
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 31727
telemt_desync_full_logged_total 9483
telemt_desync_suppressed_total 22244
telemt_desync_frames_bucket_total{bucket="1_2"} 6882
telemt_desync_frames_bucket_total{bucket="3_10"} 14080
telemt_desync_frames_bucket_total{bucket="gt_10"} 10765
telemt_pool_swap_total 107
telemt_pool_force_close_total 3522
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 787
telemt_me_draining_writers_reap_progress_total 32382
telemt_me_writer_removed_unexpected_total 2106
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4414
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29810
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2999
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 523
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28860
telemt_me_writer_teardown_success_total{mode="normal"} 34224
telemt_me_writer_teardown_noop_total 32408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66632
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 213.694556
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66632
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 787
telemt_me_refill_failed_total 3799
telemt_me_writer_restored_same_endpoint_total 1551
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 534
telemt_user_connections_total{user="hello"} 16525996
telemt_user_connections_current{user="hello"} 1760
telemt_user_octets_from_client{user="hello"} 203894997646 (189.89 GB)
telemt_user_octets_to_client{user="hello"} 1164581345511 (1.06 TB)
telemt_user_msgs_from_client{user="hello"} 373576
telemt_user_msgs_to_client{user="hello"} 663916
telemt_user_unique_ips_current{user="hello"} 849
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 103985.7 (28h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5931979
telemt_connections_bad_total 557038
telemt_connections_current 1510
telemt_connections_me_current 1510
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 123556
telemt_upstream_connect_attempt_total 56874
telemt_upstream_connect_success_total 56205
telemt_upstream_connect_fail_total 571
telemt_upstream_connect_attempts_per_request{bucket="1"} 56776
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22761
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 344
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 571
telemt_me_reconnect_attempts_total 69549
telemt_me_reconnect_success_total 1753
telemt_me_reader_eof_total 1525
telemt_me_idle_close_by_peer_total 1524
telemt_me_route_drop_no_conn_total 2375643
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4627958
telemt_me_endpoint_quarantine_total 703
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 784
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_desync_total 23209
telemt_desync_full_logged_total 8151
telemt_desync_suppressed_total 15058
telemt_desync_frames_bucket_total{bucket="1_2"} 4406
telemt_desync_frames_bucket_total{bucket="3_10"} 8982
telemt_desync_frames_bucket_total{bucket="gt_10"} 9821
telemt_pool_swap_total 107
telemt_pool_force_close_total 3112
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 388
telemt_me_draining_writers_reap_progress_total 36276
telemt_me_writer_removed_unexpected_total 1568
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3788
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34082
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2711
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33164
telemt_me_writer_teardown_success_total{mode="normal"} 37870
telemt_me_writer_teardown_noop_total 36277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74147
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.088410
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74147
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 388
telemt_me_refill_failed_total 4202
telemt_me_writer_restored_same_endpoint_total 1467
telemt_me_writer_restored_fallback_total 32
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 4620953
telemt_user_connections_current{user="hello"} 1510
telemt_user_octets_from_client{user="hello"} 123156101176 (114.70 GB)
telemt_user_octets_to_client{user="hello"} 1889307681758 (1.72 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 752
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 40821.6 (11h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3822155
telemt_connections_bad_total 138431
telemt_connections_current 1072
telemt_connections_me_current 1072
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1572269
telemt_upstream_connect_attempt_total 25213
telemt_upstream_connect_success_total 25046
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 25206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8773
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_reconnect_attempts_total 45766
telemt_me_reconnect_success_total 930
telemt_me_reader_eof_total 608
telemt_me_idle_close_by_peer_total 608
telemt_me_route_drop_no_conn_total 1010501
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1863371
telemt_me_endpoint_quarantine_total 305
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 313
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_me_writers_active_current 44
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10207
telemt_desync_full_logged_total 3521
telemt_desync_suppressed_total 6686
telemt_desync_frames_bucket_total{bucket="1_2"} 1826
telemt_desync_frames_bucket_total{bucket="3_10"} 3903
telemt_desync_frames_bucket_total{bucket="gt_10"} 4478
telemt_pool_swap_total 44
telemt_pool_force_close_total 1390
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 129
telemt_me_draining_writers_reap_progress_total 14454
telemt_me_writer_removed_unexpected_total 686
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1421
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13741
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1184
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13064
telemt_me_writer_teardown_success_total{mode="normal"} 15162
telemt_me_writer_teardown_noop_total 14456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29618
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.314816
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29618
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 129
telemt_me_refill_failed_total 2605
telemt_me_writer_restored_same_endpoint_total 832
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1867061
telemt_user_connections_current{user="hello"} 1072
telemt_user_octets_from_client{user="hello"} 53431372628 (49.76 GB)
telemt_user_octets_to_client{user="hello"} 797494956790 (742.73 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 579
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 21792.6 (6h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179944
telemt_connections_bad_total 1542
telemt_connections_current 272
telemt_connections_me_current 272
telemt_handshake_timeouts_total 4952
telemt_upstream_connect_attempt_total 10404
telemt_upstream_connect_success_total 10380
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 10402
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4422
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5884
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 223
telemt_me_reconnect_success_total 137
telemt_me_reader_eof_total 139
telemt_me_idle_close_by_peer_total 139
telemt_me_route_drop_no_conn_total 49576
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 158269
telemt_me_endpoint_quarantine_total 217
telemt_me_single_endpoint_shadow_rotate_total 192
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_desync_total 997
telemt_desync_full_logged_total 250
telemt_desync_suppressed_total 747
telemt_desync_frames_bucket_total{bucket="1_2"} 388
telemt_desync_frames_bucket_total{bucket="3_10"} 365
telemt_desync_frames_bucket_total{bucket="gt_10"} 244
telemt_pool_swap_total 24
telemt_pool_force_close_total 537
telemt_me_writer_close_signal_drop_total 21
telemt_me_draining_writers_reap_progress_total 9379
telemt_me_writer_removed_unexpected_total 135
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 626
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8892
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 535
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8842
telemt_me_writer_teardown_success_total{mode="normal"} 9518
telemt_me_writer_teardown_noop_total 9379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 18717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 18869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 18887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 18897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 18897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 18897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 18897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 18897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 18897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 18897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 18897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 18897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 18897
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.912035
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 18897
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 21
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 126
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 157975
telemt_user_connections_current{user="hello"} 272
telemt_user_octets_from_client{user="hello"} 2905761152 (2.71 GB)
telemt_user_octets_to_client{user="hello"} 92021525668 (85.70 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 103990.0 (28h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7188256
telemt_connections_bad_total 732102
telemt_connections_current 1740
telemt_connections_me_current 1740
telemt_handshake_timeouts_total 205085
telemt_upstream_connect_attempt_total 40365
telemt_upstream_connect_success_total 40211
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 40328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19928
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20242
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_reconnect_attempts_total 1538
telemt_me_reconnect_success_total 821
telemt_me_reader_eof_total 803
telemt_me_idle_close_by_peer_total 803
telemt_me_route_drop_no_conn_total 2112686
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5405429
telemt_me_endpoint_quarantine_total 723
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 799
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
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
telemt_desync_total 21236
telemt_desync_full_logged_total 6976
telemt_desync_suppressed_total 14260
telemt_desync_frames_bucket_total{bucket="1_2"} 5313
telemt_desync_frames_bucket_total{bucket="3_10"} 7688
telemt_desync_frames_bucket_total{bucket="gt_10"} 8235
telemt_pool_swap_total 115
telemt_pool_force_close_total 3109
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 378
telemt_me_draining_writers_reap_progress_total 36372
telemt_me_writer_removed_unexpected_total 774
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2893
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34272
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3021
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33263
telemt_me_writer_teardown_success_total{mode="normal"} 37165
telemt_me_writer_teardown_noop_total 36374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73539
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.602580
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73539
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 378
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 731
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 5380504
telemt_user_connections_current{user="hello"} 1740
telemt_user_octets_from_client{user="hello"} 108483415248 (101.03 GB)
telemt_user_octets_to_client{user="hello"} 2514892735812 (2.29 TB)
telemt_user_unique_ips_current{user="hello"} 798
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 103986.7 (28h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6198211
telemt_connections_bad_total 611047
telemt_connections_current 1404
telemt_connections_me_current 1404
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 170147
telemt_upstream_connect_attempt_total 56182
telemt_upstream_connect_success_total 55761
telemt_upstream_connect_fail_total 362
telemt_upstream_connect_attempts_per_request{bucket="1"} 56123
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32732
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21896
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 362
telemt_me_reconnect_attempts_total 5498
telemt_me_reconnect_success_total 1135
telemt_me_reader_eof_total 1017
telemt_me_idle_close_by_peer_total 1017
telemt_me_seq_mismatch_total 45
telemt_me_route_drop_no_conn_total 2166683
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4773443
telemt_me_endpoint_quarantine_total 831
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 795
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_desync_total 19759
telemt_desync_full_logged_total 6609
telemt_desync_suppressed_total 13150
telemt_desync_frames_bucket_total{bucket="1_2"} 4984
telemt_desync_frames_bucket_total{bucket="3_10"} 7192
telemt_desync_frames_bucket_total{bucket="gt_10"} 7583
telemt_pool_swap_total 113
telemt_pool_force_close_total 3063
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 374
telemt_me_draining_writers_reap_progress_total 34977
telemt_me_writer_removed_unexpected_total 1029
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3401
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32653
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2840
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31914
telemt_me_writer_teardown_success_total{mode="normal"} 36054
telemt_me_writer_teardown_noop_total 34981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71035
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.985622
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71035
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 374
telemt_me_refill_failed_total 252
telemt_me_writer_restored_same_endpoint_total 883
telemt_me_writer_restored_fallback_total 58
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 4776576
telemt_user_connections_current{user="hello"} 1404
telemt_user_octets_from_client{user="hello"} 89879309557 (83.71 GB)
telemt_user_octets_to_client{user="hello"} 2044381922052 (1.86 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 658
telemt_user_unique_ips_recent_window{user="hello"} 122
```