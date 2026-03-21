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

# Server Metrics 2026-03-21 21:50:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 2664.9 (0h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55675
telemt_connections_bad_total 3429
telemt_connections_current 812
telemt_connections_me_current 812
telemt_handshake_timeouts_total 2370
telemt_upstream_connect_attempt_total 1075
telemt_upstream_connect_success_total 1074
telemt_upstream_connect_attempts_per_request{bucket="1"} 1074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 387
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 682
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 28
telemt_me_reconnect_success_total 9
telemt_me_reader_eof_total 11
telemt_me_idle_close_by_peer_total 11
telemt_me_route_drop_no_conn_total 12685
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45000
telemt_me_endpoint_quarantine_total 15
telemt_me_single_endpoint_shadow_rotate_total 24
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
telemt_me_writers_active_current 43
telemt_desync_total 280
telemt_desync_full_logged_total 105
telemt_desync_suppressed_total 175
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 73
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 2
telemt_pool_force_close_total 54
telemt_me_writer_close_signal_drop_total 5
telemt_me_draining_writers_reap_progress_total 912
telemt_me_writer_removed_unexpected_total 10
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 872
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 54
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 858
telemt_me_writer_teardown_success_total{mode="normal"} 923
telemt_me_writer_teardown_noop_total 912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1835
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.689912
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1835
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 5
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 9
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 44966
telemt_user_connections_current{user="hello"} 812
telemt_user_octets_from_client{user="hello"} 627225980 (598.17 MB)
telemt_user_octets_to_client{user="hello"} 14399629704 (13.41 GB)
telemt_user_unique_ips_current{user="hello"} 347
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 16030.7 (4h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 567957
telemt_connections_bad_total 26664
telemt_connections_current 1004
telemt_connections_me_current 1004
telemt_handshake_timeouts_total 20205
telemt_upstream_connect_attempt_total 6408
telemt_upstream_connect_success_total 6286
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 6393
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3495
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_reconnect_attempts_total 560
telemt_me_reconnect_success_total 192
telemt_me_reader_eof_total 169
telemt_me_idle_close_by_peer_total 169
telemt_me_route_drop_no_conn_total 302900
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 459638
telemt_me_endpoint_quarantine_total 123
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 127
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_desync_total 2059
telemt_desync_full_logged_total 1161
telemt_desync_suppressed_total 898
telemt_desync_frames_bucket_total{bucket="1_2"} 428
telemt_desync_frames_bucket_total{bucket="3_10"} 782
telemt_desync_frames_bucket_total{bucket="gt_10"} 849
telemt_pool_swap_total 17
telemt_pool_force_close_total 502
telemt_me_writer_close_signal_drop_total 40
telemt_me_draining_writers_reap_progress_total 5612
telemt_me_writer_removed_unexpected_total 158
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 480
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5288
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 495
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5110
telemt_me_writer_teardown_success_total{mode="normal"} 5768
telemt_me_writer_teardown_noop_total 5612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 10996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 11219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 11282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 11366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 11378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 11380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 11380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 11380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 11380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 11380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 11380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 11380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 11380
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.904907
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 11380
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 40
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 129
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 459050
telemt_user_connections_current{user="hello"} 1004
telemt_user_octets_from_client{user="hello"} 7962577816 (7.42 GB)
telemt_user_octets_to_client{user="hello"} 151072069264 (140.70 GB)
telemt_user_unique_ips_current{user="hello"} 634
telemt_user_unique_ips_recent_window{user="hello"} 211
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 90890.9 (25h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7155765
telemt_connections_bad_total 552140
telemt_connections_current 3325
telemt_connections_me_current 3325
telemt_handshake_timeouts_total 223696
telemt_upstream_connect_attempt_total 32642
telemt_upstream_connect_success_total 32577
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 32584
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17749
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1439
telemt_me_reconnect_success_total 692
telemt_me_reader_eof_total 704
telemt_me_idle_close_by_peer_total 704
telemt_me_route_drop_no_conn_total 4434987
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5851030
telemt_me_endpoint_quarantine_total 568
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 673
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
telemt_me_writers_active_current 45
telemt_desync_total 24569
telemt_desync_full_logged_total 8108
telemt_desync_suppressed_total 16461
telemt_desync_frames_bucket_total{bucket="1_2"} 5270
telemt_desync_frames_bucket_total{bucket="3_10"} 9651
telemt_desync_frames_bucket_total{bucket="gt_10"} 9648
telemt_pool_swap_total 97
telemt_pool_force_close_total 3281
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 537
telemt_me_draining_writers_reap_progress_total 29735
telemt_me_writer_removed_unexpected_total 676
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2535
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27469
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3046
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 235
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26454
telemt_me_writer_teardown_success_total{mode="normal"} 30004
telemt_me_writer_teardown_noop_total 29775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59779
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 145.456217
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59779
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 537
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 618
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 5843949
telemt_user_connections_current{user="hello"} 3325
telemt_user_octets_from_client{user="hello"} 100576470284 (93.67 GB)
telemt_user_octets_to_client{user="hello"} 1878372114248 (1.71 TB)
telemt_user_unique_ips_current{user="hello"} 1382
telemt_user_unique_ips_recent_window{user="hello"} 323
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 90892.2 (25h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5847965
telemt_connections_bad_total 570568
telemt_connections_current 2351
telemt_connections_me_current 2351
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 190800
telemt_upstream_connect_attempt_total 36618
telemt_upstream_connect_success_total 36290
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 36459
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17409
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 542
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1717
telemt_me_reconnect_success_total 722
telemt_me_reader_eof_total 698
telemt_me_idle_close_by_peer_total 698
telemt_me_route_drop_no_conn_total 2031896
telemt_me_route_drop_channel_closed_total 232
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4360897
telemt_me_endpoint_quarantine_total 548
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 691
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_desync_total 20991
telemt_desync_full_logged_total 7003
telemt_desync_suppressed_total 13988
telemt_desync_frames_bucket_total{bucket="1_2"} 5091
telemt_desync_frames_bucket_total{bucket="3_10"} 8118
telemt_desync_frames_bucket_total{bucket="gt_10"} 7782
telemt_pool_swap_total 99
telemt_pool_force_close_total 3008
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 335
telemt_me_draining_writers_reap_progress_total 28355
telemt_me_writer_removed_unexpected_total 675
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2446
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26515
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2809
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25347
telemt_me_writer_teardown_success_total{mode="normal"} 28961
telemt_me_writer_teardown_noop_total 28360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57321
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 45.811750
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57321
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 335
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 621
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 4339739
telemt_user_connections_current{user="hello"} 2351
telemt_user_octets_from_client{user="hello"} 133495553513 (124.33 GB)
telemt_user_octets_to_client{user="hello"} 2010410214579 (1.83 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1031
telemt_user_unique_ips_recent_window{user="hello"} 286
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 90857.7 (25h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5774996
telemt_connections_bad_total 527796
telemt_connections_current 2146
telemt_connections_me_current 2146
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 179140
telemt_upstream_connect_attempt_total 43036
telemt_upstream_connect_success_total 42752
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 42887
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22520
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18848
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 340
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1044
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1753
telemt_me_reconnect_success_total 787
telemt_me_reader_eof_total 732
telemt_me_idle_close_by_peer_total 732
telemt_me_route_drop_no_conn_total 2051802
telemt_me_route_drop_channel_closed_total 108
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4331192
telemt_me_endpoint_quarantine_total 605
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 677
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_desync_total 20764
telemt_desync_full_logged_total 6821
telemt_desync_suppressed_total 13943
telemt_desync_frames_bucket_total{bucket="1_2"} 5146
telemt_desync_frames_bucket_total{bucket="3_10"} 7885
telemt_desync_frames_bucket_total{bucket="gt_10"} 7733
telemt_pool_swap_total 97
telemt_pool_force_close_total 2883
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 347
telemt_me_draining_writers_reap_progress_total 29781
telemt_me_writer_removed_unexpected_total 701
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2536
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27950
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2668
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26898
telemt_me_writer_teardown_success_total{mode="normal"} 30486
telemt_me_writer_teardown_noop_total 29791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60277
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 22.698591
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60277
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 347
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 681
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 4333027
telemt_user_connections_current{user="hello"} 2146
telemt_user_octets_from_client{user="hello"} 127349655507 (118.60 GB)
telemt_user_octets_to_client{user="hello"} 1978194650351 (1.80 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 958
telemt_user_unique_ips_recent_window{user="hello"} 252
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 90895.5 (25h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19521147
telemt_connections_bad_total 1333780
telemt_connections_current 3015
telemt_connections_me_current 3015
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 550715
telemt_upstream_connect_attempt_total 182685
telemt_upstream_connect_success_total 165388
telemt_upstream_connect_fail_total 15817
telemt_upstream_connect_attempts_per_request{bucket="1"} 181205
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 117734
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37646
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1154
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8854
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15817
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 59718
telemt_me_reconnect_success_total 1951
telemt_me_reader_eof_total 1282
telemt_me_idle_close_by_peer_total 1281
telemt_me_route_drop_no_conn_total 39370142
telemt_me_route_drop_channel_closed_total 117
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15996990
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 659
telemt_me_single_endpoint_outage_enter_total 111
telemt_me_single_endpoint_outage_exit_total 111
telemt_me_single_endpoint_outage_reconnect_attempt_total 239
telemt_me_single_endpoint_outage_reconnect_success_total 53
telemt_me_single_endpoint_quarantine_bypass_total 239
telemt_me_single_endpoint_shadow_rotate_total 705
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
telemt_me_writers_active_current 48
telemt_desync_total 30410
telemt_desync_full_logged_total 8982
telemt_desync_suppressed_total 21428
telemt_desync_frames_bucket_total{bucket="1_2"} 6657
telemt_desync_frames_bucket_total{bucket="3_10"} 13491
telemt_desync_frames_bucket_total{bucket="gt_10"} 10262
telemt_pool_swap_total 92
telemt_pool_force_close_total 3105
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 706
telemt_me_draining_writers_reap_progress_total 28002
telemt_me_writer_removed_unexpected_total 1832
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3817
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25761
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2598
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 507
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24897
telemt_me_writer_teardown_success_total{mode="normal"} 29578
telemt_me_writer_teardown_noop_total 28028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57606
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 205.879792
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57606
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 706
telemt_me_refill_failed_total 3520
telemt_me_writer_restored_same_endpoint_total 1370
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14245
telemt_me_writer_removed_unexpected_minus_restored_total 450
telemt_user_connections_total{user="hello"} 16122010
telemt_user_connections_current{user="hello"} 3015
telemt_user_octets_from_client{user="hello"} 164444234702 (153.15 GB)
telemt_user_octets_to_client{user="hello"} 1023550514662 (953.26 GB)
telemt_user_msgs_from_client{user="hello"} 361669
telemt_user_msgs_to_client{user="hello"} 643484
telemt_user_unique_ips_current{user="hello"} 1256
telemt_user_unique_ips_recent_window{user="hello"} 348
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 90862.6 (25h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5614562
telemt_connections_bad_total 529424
telemt_connections_current 2206
telemt_connections_me_current 2206
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 115715
telemt_upstream_connect_attempt_total 46279
telemt_upstream_connect_success_total 45757
telemt_upstream_connect_fail_total 436
telemt_upstream_connect_attempts_per_request{bucket="1"} 46193
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19217
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 330
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 436
telemt_me_reconnect_attempts_total 11237
telemt_me_reconnect_success_total 1310
telemt_me_reader_eof_total 1225
telemt_me_idle_close_by_peer_total 1225
telemt_me_route_drop_no_conn_total 2314457
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4370120
telemt_me_endpoint_quarantine_total 559
telemt_me_single_endpoint_outage_enter_total 15
telemt_me_single_endpoint_outage_exit_total 15
telemt_me_single_endpoint_outage_reconnect_attempt_total 15
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 15
telemt_me_single_endpoint_shadow_rotate_total 676
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
telemt_me_writers_active_current 49
telemt_desync_total 21962
telemt_desync_full_logged_total 7607
telemt_desync_suppressed_total 14355
telemt_desync_frames_bucket_total{bucket="1_2"} 4191
telemt_desync_frames_bucket_total{bucket="3_10"} 8527
telemt_desync_frames_bucket_total{bucket="gt_10"} 9244
telemt_pool_swap_total 92
telemt_pool_force_close_total 2729
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 344
telemt_me_draining_writers_reap_progress_total 30684
telemt_me_writer_removed_unexpected_total 1216
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3120
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28794
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2361
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 368
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27955
telemt_me_writer_teardown_success_total{mode="normal"} 31914
telemt_me_writer_teardown_noop_total 30685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62599
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.605067
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62599
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 344
telemt_me_refill_failed_total 597
telemt_me_writer_restored_same_endpoint_total 1101
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 1516
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 4359398
telemt_user_connections_current{user="hello"} 2206
telemt_user_octets_from_client{user="hello"} 116087828965 (108.12 GB)
telemt_user_octets_to_client{user="hello"} 1771296171923 (1.61 TB)
telemt_user_msgs_from_client{user="hello"} 59697
telemt_user_msgs_to_client{user="hello"} 266554
telemt_user_unique_ips_current{user="hello"} 1014
telemt_user_unique_ips_recent_window{user="hello"} 265
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 27698.5 (7h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3404405
telemt_connections_bad_total 122646
telemt_connections_current 2235
telemt_connections_me_current 2235
telemt_handshake_timeouts_total 1437569
telemt_upstream_connect_attempt_total 9232
telemt_upstream_connect_success_total 9117
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 9226
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4976
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_reconnect_attempts_total 2291
telemt_me_reconnect_success_total 313
telemt_me_reader_eof_total 228
telemt_me_idle_close_by_peer_total 228
telemt_me_route_drop_no_conn_total 957998
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1629451
telemt_me_endpoint_quarantine_total 133
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 204
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
telemt_me_writers_active_current 63
telemt_desync_total 8987
telemt_desync_full_logged_total 3012
telemt_desync_suppressed_total 5975
telemt_desync_frames_bucket_total{bucket="1_2"} 1621
telemt_desync_frames_bucket_total{bucket="3_10"} 3433
telemt_desync_frames_bucket_total{bucket="gt_10"} 3933
telemt_pool_swap_total 29
telemt_pool_force_close_total 932
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 89
telemt_me_draining_writers_reap_progress_total 8042
telemt_me_writer_removed_unexpected_total 252
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 734
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7568
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 820
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 112
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7110
telemt_me_writer_teardown_success_total{mode="normal"} 8302
telemt_me_writer_teardown_noop_total 8043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 16010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 16195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 16244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 16345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 16345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 16345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 16345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 16345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 16345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 16345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 16345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 16345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 16345
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.469111
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 16345
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 89
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 258
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 690
telemt_user_connections_total{user="hello"} 1624695
telemt_user_connections_current{user="hello"} 2235
telemt_user_octets_from_client{user="hello"} 47137855456 (43.90 GB)
telemt_user_octets_to_client{user="hello"} 696396216792 (648.57 GB)
telemt_user_unique_ips_current{user="hello"} 1009
telemt_user_unique_ips_recent_window{user="hello"} 254
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 8669.4 (2h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112113
telemt_connections_bad_total 1218
telemt_connections_current 539
telemt_connections_me_current 539
telemt_handshake_timeouts_total 3178
telemt_upstream_connect_attempt_total 3692
telemt_upstream_connect_success_total 3681
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 3691
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2114
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 75
telemt_me_reconnect_success_total 43
telemt_me_reader_eof_total 43
telemt_me_idle_close_by_peer_total 43
telemt_me_route_drop_no_conn_total 31596
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 96554
telemt_me_endpoint_quarantine_total 61
telemt_me_single_endpoint_shadow_rotate_total 77
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
telemt_desync_total 861
telemt_desync_full_logged_total 205
telemt_desync_suppressed_total 656
telemt_desync_frames_bucket_total{bucket="1_2"} 371
telemt_desync_frames_bucket_total{bucket="3_10"} 294
telemt_desync_frames_bucket_total{bucket="gt_10"} 196
telemt_pool_swap_total 9
telemt_pool_force_close_total 240
telemt_me_writer_close_signal_drop_total 12
telemt_me_draining_writers_reap_progress_total 3229
telemt_me_writer_removed_unexpected_total 43
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 211
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3061
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 238
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2989
telemt_me_writer_teardown_success_total{mode="normal"} 3272
telemt_me_writer_teardown_noop_total 3229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 6417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 6476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 6491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 6501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 6501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 6501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 6501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 6501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 6501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 6501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 6501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 6501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 6501
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.517630
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 6501
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 12
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 96414
telemt_user_connections_current{user="hello"} 539
telemt_user_octets_from_client{user="hello"} 2131763980 (1.99 GB)
telemt_user_octets_to_client{user="hello"} 61412530964 (57.19 GB)
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 90867.3 (25h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6686234
telemt_connections_bad_total 674536
telemt_connections_current 2569
telemt_connections_me_current 2569
telemt_handshake_timeouts_total 193251
telemt_upstream_connect_attempt_total 34352
telemt_upstream_connect_success_total 34216
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 34315
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16958
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17217
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_reconnect_attempts_total 1417
telemt_me_reconnect_success_total 721
telemt_me_reader_eof_total 697
telemt_me_idle_close_by_peer_total 697
telemt_me_route_drop_no_conn_total 2047031
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 22
telemt_me_route_drop_queue_full_profile_total{profile="high"} 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5115700
telemt_me_endpoint_quarantine_total 602
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 690
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
telemt_desync_total 19620
telemt_desync_full_logged_total 6544
telemt_desync_suppressed_total 13076
telemt_desync_frames_bucket_total{bucket="1_2"} 4777
telemt_desync_frames_bucket_total{bucket="3_10"} 7160
telemt_desync_frames_bucket_total{bucket="gt_10"} 7683
telemt_pool_swap_total 100
telemt_pool_force_close_total 2740
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 343
telemt_me_draining_writers_reap_progress_total 30862
telemt_me_writer_removed_unexpected_total 678
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2497
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29052
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2655
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28122
telemt_me_writer_teardown_success_total{mode="normal"} 31549
telemt_me_writer_teardown_noop_total 30864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62413
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.137231
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62413
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 343
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 645
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 5091276
telemt_user_connections_current{user="hello"} 2569
telemt_user_octets_from_client{user="hello"} 102315928844 (95.29 GB)
telemt_user_octets_to_client{user="hello"} 2386370109032 (2.17 TB)
telemt_user_unique_ips_current{user="hello"} 1051
telemt_user_unique_ips_recent_window{user="hello"} 296
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 90863.6 (25h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5698364
telemt_connections_bad_total 540427
telemt_connections_current 2599
telemt_connections_me_current 2599
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 161892
telemt_upstream_connect_attempt_total 50525
telemt_upstream_connect_success_total 50151
telemt_upstream_connect_fail_total 315
telemt_upstream_connect_attempts_per_request{bucket="1"} 50466
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19018
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 614
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 315
telemt_me_reconnect_attempts_total 4589
telemt_me_reconnect_success_total 1009
telemt_me_reader_eof_total 898
telemt_me_idle_close_by_peer_total 898
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 2101712
telemt_me_route_drop_channel_closed_total 188
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4483178
telemt_me_endpoint_quarantine_total 709
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 26
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 26
telemt_me_single_endpoint_shadow_rotate_total 689
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
telemt_desync_total 18231
telemt_desync_full_logged_total 6158
telemt_desync_suppressed_total 12073
telemt_desync_frames_bucket_total{bucket="1_2"} 4515
telemt_desync_frames_bucket_total{bucket="3_10"} 6672
telemt_desync_frames_bucket_total{bucket="gt_10"} 7044
telemt_pool_swap_total 98
telemt_pool_force_close_total 2682
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 346
telemt_me_draining_writers_reap_progress_total 29865
telemt_me_writer_removed_unexpected_total 909
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2981
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27835
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2474
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 208
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27183
telemt_me_writer_teardown_success_total{mode="normal"} 30816
telemt_me_writer_teardown_noop_total 29869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60685
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.158936
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60685
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 346
telemt_me_refill_failed_total 204
telemt_me_writer_restored_same_endpoint_total 778
telemt_me_writer_restored_fallback_total 48
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 4486897
telemt_user_connections_current{user="hello"} 2599
telemt_user_octets_from_client{user="hello"} 85451961265 (79.58 GB)
telemt_user_octets_to_client{user="hello"} 1914908903508 (1.74 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1039
telemt_user_unique_ips_recent_window{user="hello"} 259
```